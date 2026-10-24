
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out MRMS source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Manufacturing Resource Management System'
            }
        }

        stage('Test') {
            steps {
                echo 'Running application tests'
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
            echo 'MRMS pipeline completed successfully'
        }

        failure {
            echo 'MRMS pipeline failed'
        }
    }
}
