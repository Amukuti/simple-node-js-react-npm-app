pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000'
			args '--volume /var/jenkins_home/build_test:/home'
        }
    }
    stages {
        stage('Build') { 
            steps {
				docker.image('java:openjdk-7-jre').inside() {
					sh 'java -version'
				}
            }
        }
    }
}