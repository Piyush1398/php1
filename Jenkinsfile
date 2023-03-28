pipeline {
    agent { docker { image 'php:8.1.11-alpine' } } 
    stages {
        stage('verify version') {
            steps {
                sh 'php --version'
            }
        }
        stage('build') {
        steps{
        sh 'php index.php'
        }
       }
    }
}
