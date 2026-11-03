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
                echo 'Building the application'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application'
                sh 'test -f index.html'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Application deployment completed'
            }
        }
    }
}