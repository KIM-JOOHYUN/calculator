pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

    stage('compile') {
      steps {
        sh './gradlew compileJava'
      }
    }

  }
}