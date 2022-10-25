pipeline {
    agent {
        docker { image 'arm64v8/node:19-alpine3.16' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}