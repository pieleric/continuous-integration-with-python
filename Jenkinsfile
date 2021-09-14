pipeline {
    /*agent { docker { image 'python:3.5.1' } }*/
    agent {
      docker {
        image 'joltc:1.2'
        args '--privileged'
      }
    }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Test') {
            steps {
                sh 'comedi_board_info /dev/comedi0'
                sh 'py.test-3'
            }
        }
    }
}

