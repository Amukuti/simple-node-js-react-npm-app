pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				bat "choco feature enable -n=allowGlobalConfirmation"
				bat "choco install nodejs.install"
				bat "npm install"
            }
        }
    }
}