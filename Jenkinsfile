pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature-1 : Testing Webhook Trigger Building the application...'
                // Simulating a build command
                sh 'echo "feature-1: Testing Webhook Trigger  Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Webhook Trigger Running Unit Tests...'
                // Simulating a test
                sh 'echo "Testing Webhook Trigger Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Testing Webhook Trigger Deploying to Staging...'
                sh 'echo "Testing Webhook Trigger Deploy success!"'
            }
        }
    }
}
