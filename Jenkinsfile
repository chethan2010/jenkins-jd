pipeline {
    agent{
         label 'Agent-1'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'echo this is build'
            }
              options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }


        }
        stage('Test') { 
            steps {
                sh 'echo this is Test'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo this is Deploy'
            }
        }
    }
}