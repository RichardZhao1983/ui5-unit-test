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
        withAnt(installation: '/usr/local/Cellar/ant/1.10.5', jdk: '/Library/Java/JavaVirtualMachines/jdk1.8.0_60.jdk') {
          sh 'echo "good"'
        }

      }
    }
  }
}