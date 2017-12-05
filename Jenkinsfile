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
        sh '''echo "PATH = ${PATH}"
echo "M2_HOME = ${M2_HOME}"
mvn -Dmaven.test.failure.ignore=true install
pwd
'''
      }
    }
  }
}