pipeline {
  agent any
  stages {
    stage('Really') {
      steps {
        echo "Hello ${MY_NAME}!"
        echo "Username is $USER_USR"
        echo "Password is $USER_PSW"
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
    USER = credentials('password')
  }
}