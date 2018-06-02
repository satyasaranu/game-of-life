pipeline {
  agent any
  tools {
        maven 'Maven'
        jdk 'JDK1.8'
    }
  
  stages {
    stage('builds') {
      steps {
        sh 'echo " this is test build" '
        sh 'mvn -Dmaven.test.failure.ignore=true package'
      }
    }
  }
}
