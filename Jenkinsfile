pipeline {
    agent none

    stages {
        stage('Pull Request Action') {
            agent {
               docker {image 'python:2-alpine'}
            }
            steps {
                echo 'Building..'
                sh "python ${WORKSPACE}/main.py"
            }
        }
    }
}
