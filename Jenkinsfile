pipeline {
    agent {
        docker { image 'hashicorp/terraform' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'terraform --version'
                sh 'echo terraform init'
                sh 'echo terraform plan'
                sh 'echo terraform apply'
            }
        }
    }
}
