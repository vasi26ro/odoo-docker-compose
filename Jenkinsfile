pipeline {
    agent any
    stages {
        stage('Testing tools') {
            steps {
                sh """
                docker version
                docker info
                docker-compose version
                curl --version
                """
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}