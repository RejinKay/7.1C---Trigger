pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Using Maven - Test 2'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Run unit and integration tests'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Analyse code'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Perform security scan'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run integration tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy application to production server'
            }
        }
    }
}
