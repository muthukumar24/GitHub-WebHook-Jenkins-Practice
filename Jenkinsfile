pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Welcome to Jenkins!'
                echo 'Application - Build Completed'
            }
        }

        stage('Test') {
            steps {
                echo "Application - Test Completed"
            }
        }

        stage('Deploy') {
            steps {
                echo "Application - Deployment Completed"
            }
        }
    }

    post {
        success {
            echo "Application Deployed Successfully"
        }
        failure {
            echo "Application Deployment Failed"
        }
        always {
            echo "Pipeline Execution Finished"
        }
    }
}
