pipeline {
  agent any
  stages {
    stage('maven') {
      steps {
        sh 'mvn clean install '
      }
    }

    stage('nexus ') {
      steps {
        sh 'mvn deploy'
      }
    }

  }
}