pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Getting source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Flask application'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Flask application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }

    post {
        success {
            echo 'CI/CD Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
