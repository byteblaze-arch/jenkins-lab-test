pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Simulating a build command
                sh 'echo "Compile complete!"' 
            }
        }
        stage('Test') {
            steps {
                echo 'Running Unit Tests...'
                // Simulating a test
                sh 'echo "Tests Passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to Staging...'
                sh 'echo "Deploy success!"'
            }
        }
    }
}
