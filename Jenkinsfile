pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature-1 : Polling 3 Building the application...'
                // Simulating a build command
                sh 'echo "feature-1: Polling 3  Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo 'feature-1: Polling 3  Running Unit Tests...'
                // Simulating a test
                sh 'echo "feature-1: Polling 3  Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'feature-1: Polling 3 Deploying to Staging...'
                sh 'echo "feature-1: Polling 3 Deploy success!"'
            }
        }
    }
}
