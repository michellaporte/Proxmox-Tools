pipeline {
  agent any
  stages {
    stage('error') {
      agent any
      steps {
        sh 'echo "hi"'
        sh 'echo "success"'
        echo 'test passed'
      }
    }
    stage('pass') {
      steps {
        sh 'echo "part3"'
      }
    }
  }
}