pipeline {
  agent any
  stages {
    stage('say hi') {
      steps {
        sh 'echo "hi"'
      }
    }
  }
  environment {
    label = 'master'
  }
}