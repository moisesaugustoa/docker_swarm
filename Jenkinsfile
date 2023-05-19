pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                sh 'terraform --version'
            }
        }
        stage('init') {
            steps {
                sh 'echo terraform init'
            }
        }
        stage('plan') {
            steps {
                sh 'echo terraform plan'
            }
        }
        stage('apply') {
            steps {
                sh 'echo terraform apply'
            }
        }
    }
}

