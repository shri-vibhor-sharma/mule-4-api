pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        echo 'pulling code from jenkins'
        sh 'mvn clean test'
      }
    }
  }
}