pipeline {
  agent {
    docker {
      image 'node:6-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'echo "=======Build Stage=========="'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "========Testing Stage========"'
      }
    }

  }
}