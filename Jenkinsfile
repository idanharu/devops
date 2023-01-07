pipeline {
    agent {
        docker {image 'alpine:latest'}
    }

    stages {
        stage('Pull Request Action') {
            steps {
                echo 'Building..'
                sh "python ${WORKSPACE}/main.py"
            }
        }
    }
}
