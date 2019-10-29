pipeline {
  agent any
  stages {
  
    
    stage("sed") {
      parameters {
       string( name: 'ami_releaase')
               }
      steps{
    sh "touch file.txt"
    sh "cat file.txt"
         }
    }
  }
}
