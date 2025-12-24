pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature-1 : 2 Testing Webhook Trigger Building the application...'
                // Simulating a build command
                sh 'echo "feature-1: 2  Testing Webhook Trigger  Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo ' 2 Testing Webhook Trigger Running Unit Tests...'
                // Simulating a test
                sh 'echo " 2 Testing Webhook Trigger Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo ' 2 Testing Webhook Trigger Deploying to Staging...'
                sh 'echo " 2 Testing Webhook Trigger Deploy success!"'
            }
        }
    }
}
