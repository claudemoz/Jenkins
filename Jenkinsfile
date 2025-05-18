pipeline {
    agent any
    triggers {
        cron('H */4 * * 1-5')
    }
    stages {
        stage('exemple') {
            steps {
                echo 'Bonjour le monde'
            }
        }
    }
}