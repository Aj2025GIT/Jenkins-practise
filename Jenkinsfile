pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Running from GitHub Jenkinsfile"
                sh 'whoami'
            }
        }

        stage('Test') {
            steps {
                sh 'pwd'
            }
        }

        stage('Deploy') {
            steps {
                echo "Pipeline executed successfully"
            }
        }

    }
}

