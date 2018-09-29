pipeline {
    agent any
    stages {
        stage('test executables') {
            steps {
                sh 'java --version'
                sh 'export M2_HOME=/Users/phuonglam/Downloads/apache-maven-3.5.4'
                sh 'export PATH=$PATH:$M2_HOME/bin'
                sh 'echo $PATH'
                sh 'mvn --version'
            }
        }
    }
}