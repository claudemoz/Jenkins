pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Hello'
            }
            post{
                success{
                    emailext(to: 'claudetsiangana@gmail.com', body: 'test body', subject: 'test subject')
                }
            }
        }
    }
}