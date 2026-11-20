pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Source code is ready'
            }
        }

        stage('Build') {
            steps {
                echo 'Building HTML project'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing HTML file'
                bat 'if exist index.html (echo Test Passed) else (exit /b 1)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'CI Pipeline completed successfully'
            }
        }
    }
}
