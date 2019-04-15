pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''bash \'\'\'
   #!/bin/bash
   echo "hello world"
\'\'\''''
      }
    }
  }
  environment {
    init_start_e2e_instances = 'true'
  }
}