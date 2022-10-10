pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                sh 'python3 main.py'
            }
        }
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
