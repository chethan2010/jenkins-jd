pipeline {
    agent{
         label 'Agent-1'

    }
     options {
    
        timeout(time: 30, unit: 'MINUTES')
    }
    
    stages {
        stage('Build') { 
            steps {
                sh 'echo this is build'
                sh 'sleep 10'
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