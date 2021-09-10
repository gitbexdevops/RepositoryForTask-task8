pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'sudo docker start 8baf1509bc02'
                sh 'sudo docker start a21c487533aa'
            }
        }
    }
}
