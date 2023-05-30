pipeline {
  agent {
    docker {
      image 'alpine:latest'
    }

  }
  stages {
    stage('sd') {
      steps {
        sh 'echo "hello"'
      }
    }

  }
}