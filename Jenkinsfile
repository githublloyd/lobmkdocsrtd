pipeline {

  environment {
    APP = 'docs'
  }
  
  agent any

  options {
      timeout(time: 10, unit: 'MINUTES')
      disableConcurrentBuilds()
      buildDiscarder(logRotator(numToKeepStr: '10'))
  }

  stages {
    stage('Build preparation') {
      steps {
        checkout scm
      }
    }

    stage('Build the App') {
      steps {
        script {
            sh "echo Hello"
        }
      }
    }

  }

  post {
      success {
          sh "build success"
        }
      failure {
          sh "build failed"
        }
  }
}
