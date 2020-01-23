pipeline {
    agent {
        docker {
            image 'node:7-alpine'
			args '-v C:\\JenkinsDocker:/var/jenkins_home'
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