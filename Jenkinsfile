pipeline {
  agent any
  stages {
    stage('builds') {
      steps {
        sh 'echo " this is test build" '
        sh ' mvn package'
      }
    }
  }
}
