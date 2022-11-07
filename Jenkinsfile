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
        stage('Version') {
            steps {
                sh 'robot mytest.robot'
            }
        }
        stage('Reporting') {
            steps {
                archiveArtifacts 'report.html,log.html,output.xml'
            }
        }
    }
}
