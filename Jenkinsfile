pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'hello from build'
      }
    }
    stage('test') {
      steps {
        sh 'mvn -v'
      }
    }
  }
}