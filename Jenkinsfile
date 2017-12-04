pipeline {
  agent {
    docker {
      image 'centos'
    }
    
  }
  stages {
    stage('Hello') {
      steps {
        powershell(script: 'echo " Hello Naga "', returnStdout: true)
        sh 'echo "Nee PEru"'
      }
    }
  }
}