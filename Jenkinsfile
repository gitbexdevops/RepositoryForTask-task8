pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'whoami'
                sh 'sudo docker ps -a'
            }
        }
    }
}
