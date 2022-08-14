pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Git Check Out') {
            git 'https://github.com/gaurank25/NAGP-JENKINS-CICD'
        }
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
