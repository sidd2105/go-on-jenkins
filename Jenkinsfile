pipeline {
    agent any
    tools {
      go1.14.4
    }
    environment {
        GO111MODULE = 'on'
    }
    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
