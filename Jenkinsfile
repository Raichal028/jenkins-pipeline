pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh 'docker build -t my-sample-app .'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulated test step
                sh 'echo "Tests passed!"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                sh 'docker run -d -p 3000:3000 --name my-running-app my-sample-app'
            }
        }
    }
}
