pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "BUILD NUMBER: $BUILD_NUMBER. DEMO: $DEMO."'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}