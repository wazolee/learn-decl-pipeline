pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'megy ez'
      }
    }

    stage('stage2') {
      steps {
        pwsh(script: '$DEMO="alma"', returnStdout: true)
      }
    }

  }
  environment {
    DEMO = ''
  }
}