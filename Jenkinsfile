//
// Modern jenkins python example - utilizing Pipelines and Docker agent(python:3)
//

pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
              sh """
              python --version
              """
            }
        }
    }
}
