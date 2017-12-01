pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            bat 'mvn clean deploy'
          }
        }
        stage('') {
          steps {
            echo 'parallel'
          }
        }
      }
    }
  }
}