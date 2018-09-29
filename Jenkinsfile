pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'which java'
                sh 'id -un'
                sh 'java --version'
                sh 'mvn --version'
            }
        }
    }
}