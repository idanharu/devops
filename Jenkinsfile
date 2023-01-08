pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:2-alpine' 
                }
            }
            steps {
                sh 'python --version'
                sh 'pwd'
                sh 'ls'
                sh 'python main.py'
            }
        }
    }
}
