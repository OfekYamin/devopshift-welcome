
@Library('my-shared-library')
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              buildApp()
                // Build steps here
            }
        }
        stage('Test') {
            steps {
                testApp()
                // Test steps here
            }
        }
        stage('Deploy') {
            steps {
                deployApp()
                // Deploy steps here
            }
        }
    }
}
