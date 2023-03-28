pipeline {
    agent any 
    stages {
        stage('verify version') {
            steps {
                bash 'php --version'
            }
        }
        stage('build') {
        steps{
        sh 'php index.php'
        }
       }
    }
}
