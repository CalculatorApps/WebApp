pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'mvn clean deploy'
          }
        }
        stage('parallel') {
          steps {
            echo 'parallel'
            echo 'parallel'
          }
        }
      }
    }
  }
}
