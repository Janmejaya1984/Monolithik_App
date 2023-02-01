pipeline {
  agent any
  stages {
    stage('maven build') {
      steps {
        bat 'mvn clean install'
      }
    }

    stage('run the jar') {
      steps {
        bat 'java -jar university-monolithic-app-0.0.1-SNAPSHOT.jar'
      }
    }

  }
}