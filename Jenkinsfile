pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				bat "choco install nodejs.install"
				bat "npm install"
            }
        }
    }
}