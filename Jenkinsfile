pipeline {
    agent master
    stages {
        stage('Build') {
			steps {
				sh "echo env.JENKINS_HOME"
				echo env.WORKSPACE
            }
        }
    }
}