pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo \'Hello\'
'''
        echo 'Jenkins'
      }
    }

    stage('Test') {
      steps {
        retry(count: 3) {
          sh 'mkdir test'
          sh 'ls'
        }

      }
    }

  }
}