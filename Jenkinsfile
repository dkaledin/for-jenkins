pipeline {
  agent {
    docker {
      image 'node:10-alpine'
    }

  }
  stages {
    stage('Stage 1') {
      steps {
        sh 'docker ps -a'
      }
    }

  }
}