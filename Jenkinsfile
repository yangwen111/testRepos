pipeline {
  agent any
  stages {
    stage('F') {
      steps {
        sh '''node -version
npm install'''
      }
    }

    stage('Cucumber Tests') {
      steps {
        sh 'npm run acceptance:tests'
      }
    }

  }
}