pipeline{
    agent any
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
    }
  }
