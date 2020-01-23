pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-v /var/lib/jenkins/caches:/jenkins/caches' 
            args '-v /var/lib/jenkins/workspace:/jenkins/workspace' 
            args '-u root' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}