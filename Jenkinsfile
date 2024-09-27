pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('Checkout') {
            steps {
                checkout scmGit(branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/gilenz/node-hello.git']])
            }
        }
        stage('check-dir') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
