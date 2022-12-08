pipeline {
  options {
    buildDiscarder(logRotator(numToKeepStr: '30', artifactNumToKeepStr: '30'))
        }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
  
