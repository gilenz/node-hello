pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('Checkout') {
            steps {
                echo 'hello'
            }
        }
        stage('check-dir') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
