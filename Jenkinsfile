pipeline {
  agent any
  stages {
  
    stage("sed") {
      steps{
    sh "touch file.txt"
    sh "echo $ami_release >> file.txt"
    sh "cat file.txt"
    println ami_release
    println gitlab_version
    sh "echo '${ami_release}'"
    sh "sed -i "s/^ami_release/ZZ/g" "file.txt""
    sh "cat file.txt"
      }
    }
  }
}
