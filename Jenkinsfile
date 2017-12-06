pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        retry(count: 2) {
          sh 'echo %username%'
        }
        
      }
    }
  }
}