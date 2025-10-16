pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                // Corrected git step to explicitly use the 'main' branch
                git branch: 'main', url: 'https://github.com/sreekanth-sree/Jenkinstestrepo.git'
            }
        }
        stage('Build') {
            steps {
                // Corrected step: Use the 'echo' step for simple logging
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                // Corrected step: Use the 'echo' step for simple logging
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
