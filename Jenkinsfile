pipeline {
    agent any

    tools {nodejs "node"}

    stages {

        stage('Clone nodejshapi app..') {
            steps {
                git 'https://github.com/tonykambo/nodejshapi'
            }
        }
        
        stage('Install dependencies for nodejshapi app..') {
            steps {
                sh 'npm install'
            }
        }

        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('System Test') {
            steps {
                echo 'System testing...'
                sh 'npm test'
            }
        }
        
        stage('User Acceptance Testing...') {
            steps {
                echo 'User Acceptance Testing..'
            }

        }
    }
}