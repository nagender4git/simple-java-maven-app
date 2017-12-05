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
        sh '''echo $MAVEN_HOME
mvn -Dmaven.test.failure.ignore=true install'''
      }
    }
    stage('Run') {
      steps {
        sh 'mvn run'
      }
    }
  }
}