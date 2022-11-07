pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
        label 'amd64-node'
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
