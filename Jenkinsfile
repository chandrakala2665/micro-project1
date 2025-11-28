pipeline{
    agent {
        label 'slave'
    }
    stages{
        stage('server hostname')
        {
            steps{
                sh 'hostname'
            }
        }
        stage('server date')
        {
            steps{
                sh 'date'
            }
        }
        stage('server uptime')
        {
            steps{
                sh 'uptime'
            }
        }
        stage('disk usage')
        {
            steps{
                sh 'df -h'
            }
        }
            
        }
    }
  
