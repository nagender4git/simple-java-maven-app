pipeline {
  agent {
    docker {
      image 'maven'
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
        sh 'echo $MAVEN_HOME'
      }
    }
  }
}