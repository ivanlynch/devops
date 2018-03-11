pipeline {
  agent any
  stages {
    stage('Start') {
      parallel {
        stage('Start') {
          steps {
            sh '''echo "Hello World"
'''
          }
        }
        stage('Installing Dependencies') {
          steps {
            sh 'npm install'
          }
        }
      }
    }
  }
}