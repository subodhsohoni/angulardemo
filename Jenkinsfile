pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''ng update @angular/cli @angular/core
npm install --save-dev @angular-devkit/build-angular
cd AngularDemoApp
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}