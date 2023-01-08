pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:alpine3.17' 
                }
            }
            steps {
                sh 'python3 main.py'
            }
        }
    }
}
