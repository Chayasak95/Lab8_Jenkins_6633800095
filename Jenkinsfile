pipeline {
    agent any
    stages {
        stage('Build') { steps { echo 'Building...' } }
        stage('Test') { steps { sh 'robot --version || true' } }
        stage('Deploy') { steps { echo 'Deploying...' } }
    }
}
