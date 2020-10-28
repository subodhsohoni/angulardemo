pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd AngularDemoApp
npm install
ng build --prod'''
      }
    }

  }
}