pipeline {
    agent {
        label 'amd64-node'
    }
    
    stages {
        stage('Hello') {
            steps {
                docker ps -a
            }
        }   
    }
}
