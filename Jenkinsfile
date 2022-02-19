pipeline {
  agent any
  tools {
    maven "maven3"
    jdk "jdk11"
  }
  stages {
    stage("Build") {
      steps {
        sh "mvn verify"
      }  
    }
  }
}  
