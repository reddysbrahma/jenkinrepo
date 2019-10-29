pipeline {
  agent any
  stages {
  
    parameters {
       string( name: 'ami_releaase', 
            defaultValue: 'Release', 
            description: 'Configuration to build (Debug/Release/...)')
     }
    stage("sed") {
      steps{
    sh "touch file.txt"
    sh "cat file.txt"
         }
    }
  }
}
