pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''def singlyQuoted = \'Hello\'
def doublyQuoted = "World"
def username = \'Jenkins\'
echo \'Hello Mr. ${username}\'
echo "I said, Hello Mr. ${username}"'''
      }
    }
  }
}