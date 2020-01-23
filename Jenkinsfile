pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000 -v jenkins-home:/var/jenkins_home' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh "npm install" 
            }
        }
    }
}