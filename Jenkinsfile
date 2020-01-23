pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
			args '-v /var/jenkins_home/builds:/home/jenkins/agent'
			args '-e ITEM_ROOTDIR=/home/jenkins/agent'
        }
    }
    stages {
        stage('Build') { 
            steps {
				echo env.JENKINS_HOME
				echo env.ITEM_ROOTDIR
            }
        }
    }
}