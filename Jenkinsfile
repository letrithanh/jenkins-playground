def echoHi = {
    echo "Hi"
}

pipeline {
    agent {
        docker {
            image 'node'
            label 'arm64-node'   
        }
    }
    
    stages {
        stage('Test') {
            
            steps {
                sh 'node --version'
            }
        }
        
        stage('Echo') {
            steps {
                script {
                    echoHi()
                }
            }
        }
    }
}
