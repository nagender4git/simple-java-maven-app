pipeline {
  agent {
    docker {
      image 'centos6'
    }
    
  }
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            powershell(script: 'echo " Hello Naga "', returnStdout: true)
            sh 'echo "Nee PEru"'
          }
        }
        stage('display') {
          steps {
            dir(path: '/')
          }
        }
      }
    }
  }
}