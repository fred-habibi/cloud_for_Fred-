pipeline {
  agent any
  stages {
    stage('step2') {
      parallel {
        stage('step2') {
          steps {
            echo 'testing'
          }
        }
        stage('hello world') {
          steps {
            sh 'helo world'
          }
        }
      }
    }
  }
}