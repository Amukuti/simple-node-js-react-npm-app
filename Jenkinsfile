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
				sh 'echo env.JENKINS_HOME'
            }
        }
    }
}