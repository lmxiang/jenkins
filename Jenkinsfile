pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo %init_start_e2e_instances%

IF "%init_start_e2e_instances%"=="true" (
	ECHO west2 Oregon
	call aws ec2 start-instances --region us-west-2 --profile trusted --instance-ids i-0c38b21b9b0891d09
)'''
      }
    }
  }
  environment {
    init_start_e2e_instances = 'true'
  }
}