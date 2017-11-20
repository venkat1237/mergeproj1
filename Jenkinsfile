pipeline {
  agent any
  stages {
    stage('testing') {
      steps {
        sh 'echo $USER'
      }
    }
  }
  environment {
    TEST = 'DEV'
  }
}