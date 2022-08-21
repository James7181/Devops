pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'this  is stage1'
          }
        }

        stage('stage2') {
          steps {
            sh '''

touch blueocean1'''
          }
        }

      }
    }

  }
}