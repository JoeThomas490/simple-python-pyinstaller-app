pipeline {
    environment {
        PATH = "C:\\Program Files\\Git\\usr\\bin;${env.PATH}"
    }
    agent { docker {image 'python:3.5.1'}}
    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
    }
}