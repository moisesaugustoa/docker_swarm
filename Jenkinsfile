pipeline {

    agent any

    stages {
      stage('Build in Docker') {
        agent {
            docker {
                image hashicorp/terraform
                reuseNode true
            }
        }
        steps {
                sh 'echo terraform init'
        }
        steps {
                sh 'echo terraform plan'
        }
        steps {
                sh 'echo terraform apply'
        }

        }
    }
}
