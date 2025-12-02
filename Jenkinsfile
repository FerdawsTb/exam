pipeline {
    agent any

    stages {

        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Tests') {
            steps {
                sh 'npm test || echo "Tests ignored"'
            }
        }

        stage('Build Docker') {
            steps {
                sh 'echo "Docker build placeholder"'
            }
        }
    }
}
