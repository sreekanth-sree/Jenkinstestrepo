pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/sreekanth-sree/Jenkinstestrepo.git'
            }
        }
        stage('Build') {
            steps {
               sh 'echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
               sh  'echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
