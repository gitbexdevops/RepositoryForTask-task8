pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'uname -a'
                sh 'sudo docker stop a3fbca43917d'
                sh 'sudo docker stop 85d5f9bd5273'
            }
        }
    }
}
