pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('npm install') {
            steps {
                sh "apt-get update"
                sh "apt-get install -y nodejs npm"
            }
        }
        stage('check npm') {
            steps {
                sh 'npm -v'
            }
        }
    }
}
