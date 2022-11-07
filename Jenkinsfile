pipeline {
    agent {
        docker {
            image 'node'
            label 'amd64-node'   
        }
    }
    
    stages {
        stage('Test') {
            
            steps {
                sh 'node --version'
            }
        }
    }
}
