pipeline {
    agent {
        docker { image 'node:19.0.0-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}