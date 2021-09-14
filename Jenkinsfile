
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'py.test-3'
            }
        }
        stage('Test') {
            steps {
                sh 'py.test-3'
            }
        }
    }
}
