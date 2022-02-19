pipeline {
  agent any
  tools "maven3"
  tools "jdk11"
  stages {
    stage("Build") {
      steps {
        sh "mvn verify"
      }  
    }
  }
}  
