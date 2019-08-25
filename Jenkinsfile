pipeline {
  agent any
  stages {
    stage('env') {
      steps {
        sh 'git version'
        sh 'java -version'
      }
    }
  }
}