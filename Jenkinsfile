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
        sh 'yum install -y openjdk java'
      }
    }
  }
}