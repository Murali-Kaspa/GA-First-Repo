@Library('my-shared-lib') _
pipeline {
    agent any
    stages {
        stage('Welcome Page') {
            steps {
                echo "Hello World"
            }
        }
        stage('Library Test') {
            steps {
                sample()
            }
        }
    }
}
