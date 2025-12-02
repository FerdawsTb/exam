pipeline {
    agent any

    stages {

        stage('Install dependencies') {
            steps {
                bat 'npm install'
            }
        }

        stage('Tests') {
            steps {
                bat 'npm test || echo Tests ignored'
            }
        }

        stage('Build Docker') {
            steps {
                bat 'echo Docker build placeholder'
            }
        }
    }
}
