pipeline {
    agent {
        label 'amd64-node'
        docker { image 'node:16.13.1-alpine' }
    }
    
    stages {
        stage('Hello') {
            steps {
                sh 'docker ps -a'
            }
        }
        
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
