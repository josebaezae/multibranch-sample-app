pipeline {
  agent any
  options {
    buildDiscarder(logRotator(artifactNumToKeepStr: '5', daysToKeepStr: '15')),
    disableConcurrentBuilds()
    }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
  
