pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('npm install') {
            steps {
                sh 'apt install npm -y'
            }
        }
        stage('check npm') {
            steps {
                sh 'npm -v'
            }
        }
    }
}
