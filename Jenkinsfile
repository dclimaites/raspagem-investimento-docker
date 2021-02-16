pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
docker-compose stop

'''
        sh 'docker-compose up -d'
      }
    }

  }
}