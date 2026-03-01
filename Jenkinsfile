pipeline {
  agent any
  stages {
    stage('Show Vars') {
      steps {
        sh 'echo JENKINS_URL=$JENKINS_URL'
        sh 'echo BUILD_ID=$BUILD_ID'
      }
    }
  }
}
