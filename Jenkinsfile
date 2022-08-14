pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Git Check Out') {
            steps {
                git 'https://github.com/gaurank25/NAGP-JENKINS-CICD'
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
