pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Building the application using Maven...'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Running unit tests using JUnit and integration tests...'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Analysing code quality using SonarQube...'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Running security scan using OWASP Dependency-Check...'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploying application to staging server such as AWS EC2...'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Running Selenium integration tests on staging environment...'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploying application to production server...'
            }
        }
    }
}
