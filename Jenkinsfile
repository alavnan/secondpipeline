pipeline {
    agent any 
    environment {
        demovar = 'demovalue'
    }
    stages {
        stage('clone the code') {
            steps {
                sh 'echo "i am cloning the code"'
            }
        }
        stage('build') {
            steps {
                sh 'echo "i am doing the build"'
            }
        }
        stage('deploy') {
            steps {
                sh 'echo "i am deploying"'
            }
        }
        stage('Prod deploy') {
            steps {
                sh 'echo "i am deploying"'
            }
        }
    }
}
