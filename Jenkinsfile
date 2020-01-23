pipeline {
    agent {
        docker {
            image "node:7-alpine"
			args "-v /var/jenkins_home/jenkins-work:/home/jenkins/agent"
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