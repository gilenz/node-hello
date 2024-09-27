pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/gilenz/node-hello.git'
         }
        }
        stage('check-dir') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
