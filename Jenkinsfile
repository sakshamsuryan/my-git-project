pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests passed'
            }
        }
    }

    post {
        success {
            echo 'CI/CD Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
