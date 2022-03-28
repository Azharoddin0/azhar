pipeline {
  agent any
  stages {
    stage('Test 0') {
      steps {
        sh '''pwd
cal 2022'''
      }
    }

    stage('Build 1') {
      parallel {
        stage('Build 1') {
          steps {
            echo 'hello move it forward'
          }
        }

        stage('sub Build 0-1') {
          steps {
            sh 'pwd'
          }
        }

      }
    }

    stage('Deploy 2') {
      steps {
        sh 'pwd'
      }
    }

  }
}