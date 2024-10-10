pipeline {
    agent any 
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/yesminezaghdene03/5NIDS1_G1_Stationski.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying the project..."'
            }
        }
    }
}
