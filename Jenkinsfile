pipeline {
  agent any
  stages {
    stage('Build Server') {
      steps {
        echo '"Hello ${env.BRANCH_NAME}"'
      }
    }
  }
  environment {
    PIPELINE_BRANCH_WORKSPACE = 'env.WORKSPACE'
  }
}