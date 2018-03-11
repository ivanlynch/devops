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
          steps {
            sh '''echo "Hola Mundo"
'''
          }
        }
        stage('Checking NodeJS version') {
          steps {
            sh 'nodejs -v'
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