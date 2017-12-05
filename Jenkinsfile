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
        sh '''mvn -Dmaven.test.failure.ignore=true install
mvn test

'''
      }
    }
    stage('Deliver') {
      steps {
        sh './jenkins/scripts/deliver.sh'
      }
    }
  }
}