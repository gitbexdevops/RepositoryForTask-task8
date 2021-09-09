pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'whoami'
                sh 'sudo docker ps -a'
                sh 'sudo docker start 305c80ff7f9c'
            }
        }
    }
}
