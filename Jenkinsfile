pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Demo-ing a  test'
      }
    }
    stage('TEST') {
      steps {
        sh '''#!/bin/bash
read -p \'Please enter your Username: \' uservar
echo
echo "Thank you "+ uservar+ " is your username."'''
      }
    }
  }
}