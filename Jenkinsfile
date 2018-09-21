pipeline {
  agent {
    docker {
      image 'ubuntu 16.04'
    }

  }
  stages {
    stage('build') {
      steps {
        echo 'this is build stage'
      }
    }
    stage('test') {
      steps {
        echo 'this is testing'
      }
    }
    stage('verify') {
      steps {
        echo 'this is verification'
      }
    }
  }
}