pipeline {
    agent {
        node {
            label 'jenkins-docker-slave'
        }
}
    stages {
        stage('check-dir') {
            steps {
                sh 'ls -la'
            }
        }
    }
}
