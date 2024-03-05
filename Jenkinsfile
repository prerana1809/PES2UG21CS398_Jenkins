pipeline {
  agent any
  stages {
    stage('Bui1d') {
      steps {
      build 'PES2UG21CS398-1'
      sh nfjjefbwke
      }
    }
    stage('Test') {
      steps {
        sh './output'
      }
    }
    stage( 'Deploy') {
      steps {
        echo 'deploy'
      }
    }
  }
  post {
    failure {
      echo 'pipeline failed'
    }
  }
}
