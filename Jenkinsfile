pipeline {
  agent any
  stages {
    stage('Shell') {
      steps {
        sh '''ls 
pwd 
echo "Welcome to Blue Ocean Project"'''
      }
    }

    stage('Git') {
      steps {
        git(url: 'https://github.com/amitvpawar/test-nodejs-app.git', branch: 'master')
      }
    }

  }
}