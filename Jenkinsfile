pipeline {
  agent any
  stages {
  
    
    stage("sed") {
      steps{
        parameters {
       string( name: 'ami_releaase',defaultValue: "10", description: 'What version?')
               }
    sh "touch file.txt"
    sh "cat file.txt"
         }
    }
  }
}
