pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'This is a minimal pipeline'
      }
    }
    stage('Docker_stage2') {
      steps {
        sh '''#!/bin/bash
echo $USER
# echo "-----------------------------"
# npm install'''
      }
    }
  }
}