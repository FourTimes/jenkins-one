pipeline {
  agent any
  parameters {
    string(name: 'STATEMENT', description: 'What should I say?')
  }
  stages {
    stage('jobone') {
      steps {
        sh('echo ${STATEMENT}')
      }
    }
  }
}
