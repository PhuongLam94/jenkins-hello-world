pipeline {
    agent any
    stages {
        stage('test executables') {
            steps {
                sh 'java --version'
               sh 'echo $PATH'
                sh 'mvn --version'
            }
        }
        stage('compile'){
            steps{
                sh 'mvn compile'
            }
        }
        stage('verify'){
                    steps{
                        sh 'mvn verify'
                    }
                }
    }
}