pipeline {
    agent {
        docker {
            image 'node'
            label 'amd64-node'   
        }
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
