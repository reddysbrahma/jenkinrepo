pipeline {
  agent any
  stages {
    stage("sed") {
      steps{
        sh '''#!/bin/bash +x
        sed -i '/ami_release = /c ami_release = "$myVariable"' integration.tfvars
        
        '''
        sh "echo $ami_release"
        
           }
     }
  }
}
