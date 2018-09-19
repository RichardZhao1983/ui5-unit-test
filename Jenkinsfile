pipeline {
  agent {
    docker {
      image 'node:6-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('build') {
      steps {
         sh 'echo good'
         sh 'phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}