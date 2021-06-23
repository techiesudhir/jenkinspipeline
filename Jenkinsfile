pipeline {
  agent any
  stages {
    stage('Build ') {
      parallel {
        stage('Build ') {
          steps {
            echo 'Building pipeline'
          }
        }

        stage('Test') {
          steps {
            echo 'Testing pipeline $test'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy to nexus'
      }
    }

  }
  environment {
    test = 'Test_value'
  }
}