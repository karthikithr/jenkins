pipeline {
  agent any
  stages {
    stage('getgit') {
      steps {
        git(url: 'https://github.com/karthikithr/rpmbuildicon.git', branch: 'rpmbuildicon', credentialsId: 'karthikthota')
      }
    }
  }
}