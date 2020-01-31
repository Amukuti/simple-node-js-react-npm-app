pipeline {
    agent any
	environment{
		CI = 'true'
	}
    stages {
        stage('Build') { 
            steps {
				bat "choco feature enable -n=allowGlobalConfirmation"
				bat "choco install nodejs.install"
				bat "npm install"
            }
        }
		stage('Test'){
			steps {
				bat "npm test"
			}
		}
    }
}