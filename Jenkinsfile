pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'github-pat', url: 'https://github.com/KeerthanaGarimella/prog8860-cicd-lab2', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Simulating build...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }

        stage('Notify') {
            steps {
                echo 'Notification: Build completed successfully (simulation for lab submission)'
            }
        }
    }
}
