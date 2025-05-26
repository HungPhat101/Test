pipeline {
    agent {
        docker {
            image 'python:3.10.17-slim'
        }
    }
    stages {
        stage('build') {
            steps {
                echo 'Xin chào, đây là bước build!'
                sh 'python --version'
            }
        }
    }
}