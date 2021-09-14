pipeline {
    /*agent { docker { image 'python:3.5.1' } }*/
    agent { docker { image 'cip1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                sh 'py.test'
            }
        }
    }
}

