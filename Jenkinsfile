pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/mdfarhan1/Elevate-Labs.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the app...'
                sh 'echo Simulated build process'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Simulated tests'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying app...'
                sh 'echo Simulated deployment'
            }
        }
    }
}
