pipeline {
    environment {
        PATH = "C:\\Program Files\\Git\\usr\\bin;${env.PATH}"
    }
    agent none
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'python:2-alpine'
                }
            }
            steps {
                bat 'echo helloworld'
            }
        }
    }
}