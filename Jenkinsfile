pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''ls -l
ng build --no-aot --no-build-optimizer --base-href ./'''
      }
    }

  }
}