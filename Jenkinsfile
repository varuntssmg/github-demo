pipleline{
    agent any

    stages{
        stage('print Hostname'){
            step{
                sh 'Hostname'
            }
        }
        
        stage('Ip Address'){
            step{
                sh 'hostname -I'
            }
        }
        
        stage('Cpu Details'){
            step{
                sh 'lscpu'
            }
        }

        stage('Disk usage'){
            step{
                sh 'df -kh'
            }
        }

        stage('Memory usage'){
            step{
                sh 'free -h'
            }
        }
    }
}
