pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'docker-compose stop'
        bat 'docker-compose up -d'
      }
    }

  }
}