pipeline {
  agent any
  stages {
  
    stage("sed") {
      steps{
    sh "touch file.txt"
    sh "echo abc >> file.txt"
    sh "cat file.txt"
    println ami_release
    println gitlab_version
    sh "echo '${ami_release}'
      }
    }
  }
}
