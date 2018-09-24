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
    stage('Build2') {
      agent any
      environment {
        NAME = 'Branch2_name'
      }
      steps {
        sh '''echo $NAME
echo "Build2"'''
      }
    }
  }
}