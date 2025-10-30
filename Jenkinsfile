pipeline {
    //agent any
    agent {
        docker {
            image 'python:3.11-slim'
            args '-v /var/run/docker.sock:/var/run/docker.sock'
        
    stages {
        stage('Build') {
            steps {
                echo "Building the DEV branch..."
                sh 'python3 app.py'
            }
        }
    }
}
