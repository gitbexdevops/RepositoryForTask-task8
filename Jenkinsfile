pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'whoami'
                sh 'sudo docker start a3fbca43917d'
                sh 'sudo docker start 85d5f9bd5273'
            }
        }
    }
}
