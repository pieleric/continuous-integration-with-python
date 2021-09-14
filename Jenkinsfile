pipeline {
    /*agent { docker { image 'python:3.5.1' } }*/
    agent { docker { image 'cip1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh 'echo ${GIT_BRANCH}'
                sh 'git checkout ${GIT_BRANCH}'
            }
        }
        stage('Test') {
            steps {
                sh 'py.test'
            }
        }
    }
}

