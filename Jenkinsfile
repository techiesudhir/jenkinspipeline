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
            echo 'Testing pipeline'
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
}