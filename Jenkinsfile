pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        waitUntil() {
          sh 'mvn clean build'
        }
        
      }
    }
  }
}