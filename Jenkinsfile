pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000'
			args '-w "C://Program Files (x86)//Jenkins//workspace//Pipeline_master//"
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