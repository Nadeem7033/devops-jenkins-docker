pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                echo 'Code checked out from GitHub'
            }
        }

        stage('Build') {
            steps {
                echo 'Build step (Docker build will come here)'
            }
        }

        stage('Test') {
            steps {
                echo 'Test step (unit tests will come here)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy step (EC2 / ECS later)'
            }
        }
    }
}
