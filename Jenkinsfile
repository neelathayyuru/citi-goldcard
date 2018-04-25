pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/neelathayyuru/citi-goldcard/tree/master', branch: 'myregion', changelog: true, credentialsId: 'neela', poll: true)
      }
    }
  }
}