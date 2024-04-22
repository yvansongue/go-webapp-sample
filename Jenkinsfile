pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh '''pipeline {
  agent any
  stages {
    stage(\'\') {
      steps {
        sh \'go test ./...\'
      }
    }

  }
}'''
        }
      }

    }
  }