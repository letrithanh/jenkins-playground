pipeline {
    agent {
        label 'amd64-node'
    }
    
    stages {
        stage('Hello') {
            steps {
                sh 'docker ps -a'
            }
        }
        
        stage('Test') {
            agent {
                docker { image 'node:16.13.1-alpine' }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}
