pipeline {
    agent any
    tools {nodejs "nodejs"}
    environment {
        PATH = "C:\\Windows\\System32"
   }
    stages{
    stage('pull and deploy project : git') {
         steps {
               //bat 'git checkout master'
               bat 'npm install git'
               bat 'npm install'
               bat 'git checkout master'
            }
        }
    }
}