pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'hello world'
          }
        }
        stage('hello') {
          steps {
            echo 'hello'
          }
        }
      }
    }
  }
}