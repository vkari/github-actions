pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Your build steps here
                sh 'make'
            }
        }
        stage('Test') {
            steps {
                // Your test steps here
                sh 'make test'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps here
                sh 'make deploy'
            }
        }
    }
}
