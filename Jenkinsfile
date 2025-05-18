pipeline {
    agent any

    environment{
      MY_NAME = 'claude'
    }
    stages {
        stage('Build') {
            steps {
                echo "BUILD_ID: ${env.BUILD_ID}"
                echo "BUILD_NUMBER: ${env.BUILD_NUMBER}"
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "BRANCH_NAME: ${env.BRANCH_NAME}"
                echo "CI: ${env.CI}"
                echo "MY_NAME: ${env.MY_NAME}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}