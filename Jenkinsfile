pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "java --version"
                sh "mvn -v"
                sh "mvn clean install"
            }
        }
    }
}