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
            sh '''#!/bin/bash/

touch blueocean1'''
          }
        }

      }
    }

  }
}