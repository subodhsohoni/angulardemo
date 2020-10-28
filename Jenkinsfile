pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''ng build --no-aot --no-build-optimizer --base-href ./
'''
      }
    }

  }
}