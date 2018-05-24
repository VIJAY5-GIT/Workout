pipeline {
  agent any
  stages {
    stage('') {
      environment {
        TEST = 'TEST'
      }
      steps {
        bat(script: 'date', returnStatus: true, returnStdout: true)
        retry(count: 2) {
          echo 'Executed Successful'
        }

      }
    }
  }
}