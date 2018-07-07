pipeline {
  agent any
  stages {
    stage('Really') {
      steps {
        echo "Hello ${MY_NAME}!"
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}