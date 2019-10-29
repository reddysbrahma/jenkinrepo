pipeline {
  agent any
  stages {
  
    parameters {
       string( name: 'ami_releaase')
               }
    stage("sed") {
      steps{
    sh "touch file.txt"
    sh "cat file.txt"
         }
    }
  }
}
