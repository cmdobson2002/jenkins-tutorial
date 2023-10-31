/* For Mac/Linux users; Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.9.18-alpine3.17' } }
    stages {
        stage('build') {
            steps {
                sh 'pip --version'
            }
        }
    }
}