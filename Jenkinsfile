pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Saikumar6039/Devops-2025.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hello from Jenkins Pipeline! Sai Kumar is rocking it!"'
                sh 'ls -la'
                sh 'cat test.txt'
            }
        }
    }
}
