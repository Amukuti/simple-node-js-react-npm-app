pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				sh "apt install nodejs"
				sh "npm install"
            }
        }
    }
}