pipeline {
  agent any
  stages {
    stage("sed") {
      steps{
        sh '''#!/bin/bash +x
        sed -i "/ami_release = /c ami_release = ${ami_release}" integration.tfvars
        sed -i "/gitlab_version = /c gitlab_version = ${gitlab_version}" integration.tfvars
        
        '''
        sh "cat integration.tfvars"
        
           }
     }
  }
}
