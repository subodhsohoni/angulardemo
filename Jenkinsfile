pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd angulardemo
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}