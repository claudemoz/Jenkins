pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Hello'
            }
            post{
                success{
                    emailext(to: 'claudetsiangana@gmail.com', body: '$DEFAULT_CONTENT', subject: '$DEFAULT_SUBJECT')
                }
            }
        }
    }
}