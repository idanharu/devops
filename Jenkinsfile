pipeline {
    agent any
    
    stages {
        stage('Test') {
            steps {
                dir('./') {
                withPythonEnv('Python3') {
                        sh "python3 main.py"
                }
                }
            }
        }
    }
}
