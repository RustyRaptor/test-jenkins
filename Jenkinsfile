pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'https://github.com/RustyRaptor/test-jenkins.git', branch: 'main', changelog: true, poll: true)
      }
    }

  }
}