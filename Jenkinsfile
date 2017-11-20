pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        sh 'echo $USER'
      }
    }
    stage('QA') {
      steps {
        cleanWs(cleanWhenFailure: true)
      }
    }
  }
  environment {
    TEST = 'DEV'
  }
}