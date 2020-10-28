pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''npm uninstall angular-cli -g
npm uninstall angular-cli --save
npm install -g @angular/cli@latest
npm install @angular/cli --save
npm install @angular/compiler-cli --save
cd AngularDemoApp
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}