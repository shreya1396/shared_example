@Library("jenkins-shared-library") _
    stdpipeline {
        projectName = "Project1"
        serverDomain = "Project1 Server Domain }

pipeline {
  agent any
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
