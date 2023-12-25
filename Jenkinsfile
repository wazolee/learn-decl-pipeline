pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "megyez $BUILD_NUMBER $DEMO"'
      }
    }

  }
  environment {
    DEMO = 'lama'
  }
}