pipeline {
  agent any
  stages {
    stage('message') {
      steps {
        echo 'bonjour'
      }
    }

    stage('build') {
      steps {
        sh 'dotnet build yvesbissai.sln'
      }
    }

  }
}