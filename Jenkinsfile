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
        sh 'mvn clean build'
      }
    }
  }
}