pipeline {
    agent {
        docker {image 'node:16-alpine'}
    }

    stages {
        stage('Test') {
            steps {
                echo 'Hello World'
                sh 'node --version'
            }
        }
    }
}
