pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000'
			args '--volume /var/jenkins_home/build_test:/home'
			args '-u 0:0'
			args '-d=false'
        }
    }
    stages {
        stage('Build') { 
            steps {
				sh "echo env.JENKINS_HOME"
				echo env.WORKSPACE
            }
        }
    }
}