pipeline {
  agent any
  stages {
    stage('echo') {
      parallel {
        stage('echo') {
          steps {
            sh 'echo "alihan"'
          }
        }

        stage('kod') {
          steps {
            sh '''pwd
ls
docker compose up'''
          }
        }

      }
    }

  }
}