pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                bat 'docker build -t my-sample-app .'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Simulated test step
                bat 'echo Tests passed!'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                bat 'docker run -d -p 3000:3000 --name my-running-app my-sample-app'
            }
        }
    }
}
