pipeline {
  agent none
  stages {
    stage('code') {
      steps {
        git(url: 'https://github.com/altafnoor2013/altafgit.git', branch: 'master')
      }
    }

    stage('build') {
      steps {
        echo 'POLL'
      }
    }

  }
}