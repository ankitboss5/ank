pipeline {
  agent any
  stages {
    stage('clone') {
      steps {
        git(url: 'https://gitlab.com/aparmar4/ankit.git', branch: 'main', poll: true, credentialsId: 'aparamr4')
      }
    }

  }
}