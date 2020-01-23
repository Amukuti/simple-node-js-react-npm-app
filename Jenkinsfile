pipeline {
    agent {
        docker {
            image "node:7-alpine"
			args "-v /C/Users/Amukuti/Project/JenkinsTemp:/home/jenkins/agent -v /C/Users/Amukuti/Project/JenkinsHome:/var/jenkins_home"
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