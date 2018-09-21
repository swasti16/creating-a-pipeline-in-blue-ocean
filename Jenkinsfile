pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'This is a minimal pipeline'
          }
        }
        stage('print 2') {
          steps {
            echo 'Pipeline 2'
          }
        }
      }
    }
  }
}