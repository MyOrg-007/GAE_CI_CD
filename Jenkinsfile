pipeline {
  agent any
    
  tools {nodejs "node"}
    
  stages {
        
    // stage('Git') {
    //   steps {
    //     git 'https://github.com/****/****'
    //   }
    // }
     
    stage('Build') {
      steps {
        sh 'npm install'
        sh 'npm run build --if-present'
      }
    } 
    
            
    // stage('Test') {
    //   steps {
    //     sh 'node test'
    //   }
    // }
  }
}