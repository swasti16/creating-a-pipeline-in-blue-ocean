pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''echo $USER
echo $0'''
          }
        }
        stage('print 2') {
          steps {
            sh 'echo "In print 2"'
          }
        }
      }
    }
  }
}