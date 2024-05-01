pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                // Your build steps here
                sh 'ls -ltr'
            }
        }
        stage('Test') {
            steps {
                // Your test steps here
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps here
                sh 'hostname'
            }
        }
    }
}
