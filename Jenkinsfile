pipeline {
  agent any
  parameters {
    string(name: 'STATEMENT', defaultValue: 'hello', description: 'What should I say?')
  }
  stages {
    stage('jobone') {
      steps {
        sh('echo ${STATEMENT}')
      }
    }
  }
}
