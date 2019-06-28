pipeline {
  agent any
  stages {
    stage('checkout') {
      parallel {
        stage('checkout') {
          steps {
            sh 'ls'
          }
        }
        stage('build') {
          steps {
            sh 'echo \'test\''
          }
        }
      }
    }
  }
}