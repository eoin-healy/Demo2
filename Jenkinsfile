pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''sh(\'\'\'#!c:\\path\\to\\bash.exe
read -p \'Please enter your Username: \' uservar
echo
echo "Thank you "+ uservar+ " is your username."
echo "I am in bash"
\'\'\')
'''
      }
    }
  }
}