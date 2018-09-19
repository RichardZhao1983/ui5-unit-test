pipeline {
  agent any
  stages {
    stage('build') {
      steps {
         sh '#!/bin/bash -ilex echo good'
         sh ' #!/bin/bash -ilex phantomjs ./src/test/js/runner.js ./src/test/js/qunit.html'
      }
    }
  }
}