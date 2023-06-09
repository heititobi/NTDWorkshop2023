pipeline {
    agent any
    stages {
        stage('Build API container') {
            steps {
                sh 'docker build . -t heiti/movie-api'
            }
        }
    }
}
