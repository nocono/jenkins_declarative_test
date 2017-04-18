pipeline {
    agent any
    stages {
        stage('Build') {
            steps{
              echo "Test"
            }
        }
        stage('Test') {
            steps{
                echo "Test -Stage"
             }
        }
    }
    post {
        always {
            echo "POST - always"
        }
        success {
            echo "POST  - success"
        }
        failure {
            echo "POST - failure"
        }
 }
}
