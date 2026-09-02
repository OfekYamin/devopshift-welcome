
@Library('my-shared-library')
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              mylibrary.buildApp()
                // Build steps here
            }
        }
        stage('Test') {
            steps {
                mylibrary.testApp()
                // Test steps here
            }
        }
        stage('Deploy') {
            steps {
                mylibrary.deployApp()
                // Deploy steps here
            }
        }
    }
}
