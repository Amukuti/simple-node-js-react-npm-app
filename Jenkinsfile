pipeline {
    agent {
        docker {
            image 'node:7-alpine'
			args '-v /var/run/docker.sock:/var/run/docker.sock'
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'node --version'
            }
        }
    }
}