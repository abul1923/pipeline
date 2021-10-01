pipeline {
    agent any
    stages {
        stage("HOSTNAME"){
            steps  {
                sh 'hostname'
            }
        }
        stage("date"){
            steps  {
                sh'''
                
                date
                uname -mrs
                df -Th
                
                '''
            }
        }
    }
}
