pipeline {
    agent {
        docker {
            image 'python:3.10.17-slim'
        }
    }
    stages {
        stage('build') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    retry(2) {
                        echo 'Xin chào, đây là bước build!'
                        sh 'python --version'
                    }
                }
            }
        }
    }
}