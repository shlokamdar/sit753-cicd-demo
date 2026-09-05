pipeline {
    agent any
    stages {
        stage('Build') {
            steps { echo 'Compiling and packaging code using Maven' }
        }
        stage('Unit and Integration Tests') {
            steps { echo 'Running unit tests with JUnit and integration tests with Postman/Newman' }
        }
        stage('Code Analysis') {
            steps { echo 'Analysing code quality using SonarQube' }
        }
        stage('Security Scan') {
            steps { echo 'Scanning for vulnerabilities using OWASP Dependency-Check' }
        }
        stage('Deploy to Staging') {
            steps { echo 'Deploying application to AWS EC2 staging instance using Ansible' }
        }
        stage('Integration Tests on Staging') {
            steps { echo 'Running integration tests on staging using Selenium' }
        }
        stage('Deploy to Production') {
            steps { echo 'Deploying application to AWS EC2 production instance using AWS CodeDeploy' }
        }
    }
}
