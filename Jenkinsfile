pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/JaiberS/proyecto-jenkins.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy Simulation') {
            steps {
                echo 'Simulating deployment...'
            }
        }
    }
}