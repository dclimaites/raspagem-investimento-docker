pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
/usr/local/bin/docker-compose stop

'''
        sh '/usr/local/bin/docker-compose up -d'
      }
    }

  }
}