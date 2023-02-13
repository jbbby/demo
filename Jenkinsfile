pipeline {
  agent any
  stages {
    stage('Checkout'){
      steps {
        sh "echo starting"
      }
    }
    stage('Build'){
      steps {
        sh "echo build"
      }
    }
    stage('ECR'){
      steps {
        sh "echo ecr push"
      }
    }
  }
}
