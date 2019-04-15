pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo "apt-get update"
./jenkins/scripts/test.sh'''
      }
    }
  }
}