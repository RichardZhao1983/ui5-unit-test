pipeline {
  agent any
  stages {
    stage('build') {
      steps {
         sh 'echo good'
         #!/bin/bash -ilex sh 'phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}