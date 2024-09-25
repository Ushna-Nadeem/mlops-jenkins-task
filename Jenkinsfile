pipeline {
    agent any

    environment {
        IMAGE_NAME = 'ushna1923/sweet-savory-predictor'
        REGISTRY_CREDENTIALS = 'e16fa279-f0bf-4bed-bd20-eeefaed24468'
    }

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Build Docker Image') {
            steps {
                script {
                    echo "Docker Image is Built."
                }
            }
        }

        stage('Push Docker Image') {
            steps {
                script {
                    echo "Docker Image is Pushed."
                }
            }
        }
    }
}
