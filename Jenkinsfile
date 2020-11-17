pipeline {
  agent any
  stages {
    stage('checkout'){
      steps {
        deleteDir()
        git branch: 'master', url: 'https://github.com/AparnaBalasundar/test.git'
      }
    }
  }
}
