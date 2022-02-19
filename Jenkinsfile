pipeline {
  agent any
  tools {
    maven "maven3"
    jdk "jdk11"
  }
  stages {
    stage("Build") {
      steps {
        withMaven {
          sh "mvn verify -e -B -V"
        }  
      }  
    }
  }
}  
