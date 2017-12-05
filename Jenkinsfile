pipeline {
  agent {
    docker {
      image 'centos'
    }
    
  }
  stages {
    stage('Initialize') {
      steps {
        sh 'echo "Nee PEru"'
      }
    }
    stage('Build') {
      steps {
        tool(name: 'maven', type: 'build')
      }
    }
  }
}