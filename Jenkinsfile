pipeline {
    agent any 
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
