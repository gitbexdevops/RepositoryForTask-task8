pipeline {
  agent { label 'agent'}
  stages {
    stage('Back-end') {
      agent {
        docker { start dreamy_clarke }
      }
      
    }
  }
}
