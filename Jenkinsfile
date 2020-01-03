pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    stage('Cloning Git') {
      steps {
        git 'https://github.com/Mlan2312/NodeApp.git'
      }
    }
        
    stage('Run App') {
      steps {
        'npm install'
      }
    }
       stage('Run App') {
      steps {
        'node main'
      }
    }
  }
}
