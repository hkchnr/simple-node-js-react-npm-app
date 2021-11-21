pipeline {
   agent none
    stages {
        agent {
    docker {
        dockerfile true
        label 'docker'
    }
}
    }

        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }


