pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps{
        git branch: 'main', url: 'https://github.com/prashanth19975/demo-counter-app.git'
      }
    }
     stage('Maven Build'){
       steps{
         sh 'mvn clean install'
         }
      }
    
     }    
} 
