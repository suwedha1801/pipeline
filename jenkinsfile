pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Example: sh 'make build'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh './run_tests.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Example: sh './deploy.sh'
            }
        }
    }
}
