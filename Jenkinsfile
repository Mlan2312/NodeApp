pipeline {
    agent any
    
    tools {
        nodejs 'node:12.13'
    }
    stages {
      
       stage('Cloning Git') {
      steps {
        git 'https://github.com/Mlan2312/NodeApp.git'
      }
       }
      
        stage('build') {
            steps {
                sh 'npm install'
                sh 'node main.js'
            }
        }
    }
}
