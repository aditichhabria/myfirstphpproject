pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        bat 'php -version'
      }
    }
    stage('hello') {
      steps {
        bat 'php index.html'
          } 
      }
  }
}
