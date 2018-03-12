pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Comenzando la face de build'
            }
            steps {
                echo 'Building dependencies'
                sh 'node -v'
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}