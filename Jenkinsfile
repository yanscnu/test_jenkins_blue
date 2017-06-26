pipeline {
  agent any
  stages {
    stage('') {
      steps {
        parallel(
          "test111": {
            sh 'echo 111'
            
          },
          "test222": {
            sh 'echo 222'
            
          }
        )
      }
    }
  }
}