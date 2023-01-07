pipeline {
    agent any

    stages {
        stage('Pull Request Action') {
            steps {
                echo 'Building..'
                sh 'python $(WORKSPACE)/main.py'
            }
        }
    }
}
