pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''docker-compose stop
docker-compose up -d'''
      }
    }

  }
}