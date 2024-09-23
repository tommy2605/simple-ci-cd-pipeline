pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/tommy2605/simple-ci-cd-pipeline.git'
            }
        }
        stage('Install Dependencies') {
            steps {
                sh 'pip3 install -r requirements.txt'
            }
        }
        stage('Build') {
            steps {
                echo 'Building Python app...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here if any
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Python app...'
            }
        }
    }
}
 
