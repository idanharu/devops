pipeline {
    agent any

    stages {
        stage('Pull Request Action') {
            steps {
                echo 'Building..'
                sh "python $(workspace)/main.py"
            }
        }
    }
}
