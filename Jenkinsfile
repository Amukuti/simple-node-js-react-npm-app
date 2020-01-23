pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000 -Dorg.jenkinsci.plugins.durabletask.BourneShellScript.LAUNCH_DIAGNOSTICS=true' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh "npm install" 
            }
        }
    }
}