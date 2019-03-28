pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        powershell 'mvn clean test'
      }
    }
  }
}