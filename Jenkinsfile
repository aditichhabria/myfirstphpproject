pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        bat 'php -version'
      }
    }
    stage('copy php code on xampp server') {
      steps {
        bat 'xcopy /s * D:\xampp\htdocs\myfirstproject1 /Y'
      }
    }
      stage('copy php code on xampp server') {
      steps {
        bat 'php -S localhost:8012/myfirstproject1/index.html'
      }
    }
       
  }
}
