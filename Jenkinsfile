pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				sh "choco install nodejs"
				sh "npm install"
            }
        }
    }
}