pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('npm install') {
            steps {
                sh 'apt install npm'
            }
        }
        stage('check-dir') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
