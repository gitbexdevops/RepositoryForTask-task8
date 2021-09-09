pipeline {
 agent any
  agent {
    docker { start dreamy_clarke }
  }
  stages {
    stage('Test') {
      steps {
        sh 'docker ps'
      }
    }
  }
}
