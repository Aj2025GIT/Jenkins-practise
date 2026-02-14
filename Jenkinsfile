pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t jenkins-demo ./jenkins-docker'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run --rm jenkins-demo'
            }
        }

    }
}

