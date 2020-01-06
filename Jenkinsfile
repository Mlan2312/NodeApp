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
                 'npm install'
                 'node main.js'
            }
        }
    }
}
