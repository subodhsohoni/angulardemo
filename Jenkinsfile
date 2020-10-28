pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd AngularDemoApp
ng build --prod --aot=true'''
      }
    }

  }
}