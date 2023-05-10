pipeline {
    agent any
    stages {
        stage('Build'){
            steps {
                sh "echo hello"
              }
        }
            
        stage('Test'){
            steps {
                sh "ls -la"
                sh "touch testfile.txt"
              }
        }
            
        stage('Deploy'){
            steps {
                sh "pwd"
                sh "rm -f testfile.txt"
              }
        }
    }
}
