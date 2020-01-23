pipeline {
    agent {
        docker {
            image "node:7-alpine"
			args "-v C:\Users\Amukuti\Project\JenkinsTemp:/home/jenkins/agent"
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