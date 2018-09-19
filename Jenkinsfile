pipeline {
  agent {
     docker {
            image 'maven:3-alpine'
            args '-v /root/.m2:/root/.m2'
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