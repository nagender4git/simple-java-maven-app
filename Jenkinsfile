pipeline {
  agent {
    docker {
      image 'maven3.5'
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