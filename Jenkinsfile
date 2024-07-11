pipeline {
    agent any
    environment {
        NODEJS_HOME = tool 'NodeJS' // Assumes NodeJS is installed and configured in Jenkins
        PATH = "${env.NODEJS_HOME}/bin:${env.PATH}"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'yum npm install' 
            }
        }
    }
}
