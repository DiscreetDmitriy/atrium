pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://github.com/DiscreetDmitriy/atrium', branch: 'master')
      }
    }
    stage('error') {
      steps {
        sh './gr'
      }
    }
  }
}