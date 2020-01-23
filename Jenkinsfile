pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000 -v C:\JenkinsAgent:/tmp' 
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