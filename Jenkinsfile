pipeline {
  agent{
    label 'slave1'
  }
  stages {
    stage('checkout'){
      steps {
        deleteDir()
        git branch: 'master', url: 'https://github.com/AparnaBalasundar/test.git'
      }
    }
  }
}
