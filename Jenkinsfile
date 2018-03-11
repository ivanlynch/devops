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
        stage('Checking PhantomJS version') {
          steps {
            sh 'phantomjs -v'
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