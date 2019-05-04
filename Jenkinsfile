pipeline {
  agent any
  stages {
    stage('pull git code') {
      steps {
        git(url: 'https://github.com/shri-vibhor-sharma/mule-4-api.git', poll: true)
      }
    }
  }
  environment {
    ENv = 'DEV'
  }
}