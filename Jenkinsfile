pipeline {
  agent any
  stages {
    stage('Build Server') {
      steps {
        build 'Starborne Pipeline - Compile Server'
      }
    }
  }
  environment {
    PIPELINE_BRANCH_WORKSPACE = 'env.WORKSPACE'
  }
}