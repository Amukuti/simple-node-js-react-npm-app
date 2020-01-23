pipeline {
    agent {
        docker {
            image 'node:7-alpine'
			args '-v /var/jenkins_home:/var/jenkins_home'
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