pipeline {
    agent any

    tools {nodejs "node"}

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'npm config ls'
            }
        }
        stage('System Test') {
            steps {
                echo 'System testing...'
            }
        }
        stage('User Acceptance Testing...') {
            steps {
                echo 'User Acceptance Testing..'
            }

        }
    }
}