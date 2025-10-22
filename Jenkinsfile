pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the MAIN branch..."
                sh 'python3 app.py'
            }
        }
    }
}
