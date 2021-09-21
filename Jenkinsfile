pipeline {
 agent { label 'agent1'}
  stages {
        stage('Test') {
            steps {
                sh 'sudo docker start 48f8b64c6d35'
                sh 'sudo docker start c17609774f24'
            }
        }
    }
}
