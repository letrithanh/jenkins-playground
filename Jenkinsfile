node ("amd64-node") {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    
    stage('Test') {
        sh 'node --version'
    }
    
}
pipeline {
    agent {
        label 'amd64-node'
    }
    
    stages {
        stage('Test') {
            sh 'docker ps -a'
        }    
    }
}
