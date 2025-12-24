pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'feature-1 : Building the application...'
                // Simulating a build command
                sh 'echo "feature-1: Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo 'feature-1: Running Unit Tests...'
                // Simulating a test
                sh 'echo "feature-1: Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'feature-1: Deploying to Staging...'
                sh 'feature-1: echo "Deploy success!"'
            }
        }
    }
}
