pipeline {
  agent any
  stages {
    stage('build') {
      steps {
	 sh '#!/bin/bash -ilex'
         sh 'echo good'
         sh 'phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}