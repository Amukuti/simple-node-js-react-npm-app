pipeline {
    agent {
        docker {
            image "node:7-alpine"
			args "-w /C/Users/Amukuti/Project/JenkinsTemp"
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