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
      post {
        always {
            sh 'curl -X POST --user admin:118215dd370e9a039cf47bf29d59790f5f  http://ado.dodonotdo.in:8080/job/demo/job/two/buildWithParameters?STATEMENT=${STATEMENT}'
        }

    }
}
