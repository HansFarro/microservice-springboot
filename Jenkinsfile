pipeline {
    agent {
        docker {
            image 'jenkins/ssh-agent'
        }
    }
    stages {
        stage('Build'){
            steps{
                sh 'java --version'
                withMaven(){
                    sh 'mvn clean install'
                }
            }
        }
    }
}