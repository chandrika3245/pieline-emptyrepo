pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        echo 'i want to develop the code'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo ' i want to test the code'
          }
        }

        stage('Deploy') {
          steps {
            echo 'deploy the code'
          }
        }

      }
    }

  }
}