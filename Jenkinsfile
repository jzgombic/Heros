pipeline {
  agent any
  stages {
    stage('NPM Install') {
      steps {
        bat 'npm install'
      }
    }

    stage('Build') {
      steps {
        bat 'ng build --prod'
      }
    }

  }
}