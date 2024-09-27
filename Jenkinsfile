pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('npm install') {
            steps {
                sh 'sudo apt install npm -y'
            }
        }
        stage('check npm') {
            steps {
                sh 'npm -v'
            }
        }
    }
}
