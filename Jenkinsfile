pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature-1 : Polling Building the application...'
                // Simulating a build command
                sh 'echo "feature-1: Polling Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo 'feature-1: Polling Running Unit Tests...'
                // Simulating a test
                sh 'echo "feature-1: Polling Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'feature-1: Polling 2 Deploying to Staging...'
                sh 'echo "feature-1: Polling 2 Deploy success!"'
            }
        }
    }
}
