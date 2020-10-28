pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd AngularDemoApp
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}