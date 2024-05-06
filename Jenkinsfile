pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh 'docker build -t todo .'
        sh 'docker run -d -p 8800:8000 todo'
      }
    }
  }
}
