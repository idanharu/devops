//
// Modern jenkins python example - utilizing Pipelines and Docker agent(python:3)
//

pipeline {
    agent {
      docker {
        image 'python:3'
        label 'my-build-agent'
      }
    }
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
