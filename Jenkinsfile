pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
				withDockerContainer (image: 'node:7-alpine'){
					sh 'node --version'
				}
            }
        }
    }
}