pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                bat 'python hello.py'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                bat 'python hello.py'
            }
        }
    }
}