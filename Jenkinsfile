pipeline {
  agent any
  stages {
    stage('Install') {
      agent {
        docker {
          image 'node:12-alpine'
        }

      }
      steps {
        sh 'yarn add typescript'
      }
    }

    stage('App Name') {
      steps {
        input(message: 'Which App do you want to deploy?', id: 'app-name')
      }
    }

  }
}