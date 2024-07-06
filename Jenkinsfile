pipeline {
    agent {
        docker { image 'docker/welcome-to-docker' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'docker version'
            }
        }
    }
}