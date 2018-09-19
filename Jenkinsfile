pipeline {
  agent any
  stages {
    stage('build') {
      steps {
         sh 'phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}