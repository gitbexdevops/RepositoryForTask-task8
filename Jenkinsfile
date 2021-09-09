pipeline {
 agent { label 'agent'}
  stages {
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
