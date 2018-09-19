pipeline {
  agent {


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