pipeline {
    agent any

    stages {
        stage('Test') {
          steps {
            echo "Running Test..."
          }
        }

        stage('Build') {
          steps {
            echo 'Building the app...'
          }
        }

        stage('Deploy') {
          steps {
            echo 'Deploying app...'
          }
        }
    }

    post {
      success {
        echo 'Pipeline completed successfully!'
      }
      failure {
        echo 'Pipeline failed!'
      }
    }
}
