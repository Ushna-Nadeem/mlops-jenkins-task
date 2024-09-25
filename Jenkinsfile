pipeline {
    agent any

    environment {
        IMAGE_NAME = 'ushna1923/sweet-savory-predictor-classtask3'
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
                    echo
                }
            }
        }

        stage('Push Docker Image') {
            steps {
                script {
                    docker.withRegistry('', REGISTRY_CREDENTIALS) {
                        docker.image("$IMAGE_NAME:latest").push()
                    }
                }
            }
        }

        stage('Clean Up') {
            steps {
                script {
                    sh 'docker rmi $IMAGE_NAME:latest'
                }
            }
        }
    }
}
