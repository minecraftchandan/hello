pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/minecraftchandan/hello.git'
            }
        }
        
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
        
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}