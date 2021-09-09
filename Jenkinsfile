pipeline {
  agent { label 'agent1'}
  stages {
    stage('Back-end') {
      agent {
        docker { start dreamy_clarke }
      }
      
    }
  }
}
