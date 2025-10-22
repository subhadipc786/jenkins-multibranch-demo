pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the DEV branch..."
                sh 'python3 app.py'
            }
        }
    }
}
