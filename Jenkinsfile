pipeline {
    agent { docker { image 'node:12.13.1' } }
    stages {
      
       stage('Cloning Git') {
      steps {
        git 'https://github.com/Mlan2312/NodeApp.git'
      }
       }
      
        stage('build') {
            steps {
                sh 'node main.js'
            }
        }
    }
}
