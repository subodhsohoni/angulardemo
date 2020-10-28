pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''cd AngularDemoApp
npm install
ng build --prod
mkdir /var/lib/jenkins/buildoutput/$BUILD_NUMBER
cp -a dist/. /var/lib/jenkins/buildoutput/$BUILD_NUMBER'''
      }
    }

  }
}