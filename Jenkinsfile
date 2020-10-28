pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd AngularDemoApp
npm install
ng build --prod
cp dist/ ~/ansible-demo/buildoutput'''
      }
    }

  }
}