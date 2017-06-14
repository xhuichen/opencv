pipeline {
  agent {
    node {
      label 'maven-jdk1.8'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'mvn clean package'
      }
    }
  }
}