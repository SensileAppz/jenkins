pipeline {
  agent any
  stages {
    stage('Build First Application') {
      steps {
        build(propagate: true, wait: true, job: 'first-application')
      }
    }
  }
}