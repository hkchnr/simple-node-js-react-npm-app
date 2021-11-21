pipeline {
   agent none
    stages {
         agent{
   docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }

        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}

