pipeline {
  agent any
  stages {
    stage('log') {
      parallel {
        stage('log') {
          steps {
            sh 'ls --all'
          }
        }

        stage('Log2') {
          steps {
            fileExists 'index.js'
            echo 'HEllo word'
          }
        }

      }
    }

  }
}