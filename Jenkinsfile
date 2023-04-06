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
    stage('Sonar'){
      steps {
        sh "echo Sonar"
      }
    }
    stage('ECR'){
      steps {
        sh "echo ecr push"
      }
    }
    stage('EKS'){
      steps {
        sh "echo eks push"
      }
    }
  }
}
