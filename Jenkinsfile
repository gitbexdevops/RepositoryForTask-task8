pipeline {
 agent { label 'agent'}
  stages {
    agent {
     stage('Test') {
      agent {
         docker { start dreamy_clarke }
        } 
      steps {
        sh 'docker ps'
      }
    }
  }
 }
}
