pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        build(job: 'Pruebas', quietPeriod: 1)
      }
    }
  }
}