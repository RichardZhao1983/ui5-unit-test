pipeline {
  agent any
  stages {
    stage('build') {
      steps {
         sh 'echo $PATH'
	 sh 'who am i'
         sh 'phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}