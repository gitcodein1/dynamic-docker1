pipeline {
  agent {
    dockerfile {
      filename 'Dockerfile1'
    }
  }
  stages {
    stage("TEST") {
      steps {
        sh 'ls -l'
      }
    }  
  }
}
