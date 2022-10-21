Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'python:3.8.0' }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
