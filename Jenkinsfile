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
                sh "pwd"
                sh "touch testfile.txt"
                sh "ls -la"
              }
        }
            
        stage('Deploy'){
            steps {
                sh "rm -f testfile.txt"
                sh "ls -la"
              }
        }
    }
}
