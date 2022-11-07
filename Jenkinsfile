pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Terve'
            }
        }
        stage('Version') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
