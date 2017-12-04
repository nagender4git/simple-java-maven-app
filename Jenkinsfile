pipeline {
  agent {
    docker {
      image 'centos'
      args 'latest'
    }
    
  }
  stages {
    stage('Hello') {
      steps {
        powershell(script: 'echo " Hello Naga "', returnStdout: true)
      }
    }
  }
}