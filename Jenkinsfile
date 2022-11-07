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
    }
}
