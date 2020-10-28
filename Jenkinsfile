pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''npm install
npm install -g @angular/cli@latest
ng build --no-aot --no-build-optimizer --base-href ./
'''
      }
    }

  }
}