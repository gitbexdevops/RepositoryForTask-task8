pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'whoami'
                sh 'sudo docker ps -a'
                sh 'sudo docker start hello-world'
            }
        }
    }
}
