pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'BUILD NUMBER: $BUILD_NUMBER. DEMO: $DEMO.'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}