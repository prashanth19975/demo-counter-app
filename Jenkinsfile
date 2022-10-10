pipeline {
  agent any
  stages {
    stage('Git Checkout') {
      steps{
        git branch: 'main', url: 'https://github.com/prashanth19975/demo-counter-app.git'
      }
    }
     stage('Unit testing'){
       steps{
         sh 'mvn test'
         }
         }
     stage('Integration testing'){
       steps{
         sh 'mvn verify -Dskiunittests'
         }
         }
     }    
} 
