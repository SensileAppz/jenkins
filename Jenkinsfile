pipeline {
  agent any
  stages {
    stage('Build First Application') {
      steps {
        build(propagate: true, job: 'first-application')
      }
    }
  }
}