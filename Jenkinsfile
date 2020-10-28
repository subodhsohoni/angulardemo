pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''npm install
ng update
npm update
cd AngularDemoApp
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}