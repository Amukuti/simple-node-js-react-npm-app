pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000 --volumes-from fcca92e26042363176f1e0fe97cd6297a61ae1bc8ea591793f15a464603f3913' 
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