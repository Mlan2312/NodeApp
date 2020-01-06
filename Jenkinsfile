pipeline {
    agent any
   
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
