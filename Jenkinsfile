pipeline {
    agent { label '10.100.30.83' }
    stages {
        stage('Clone repository') {
            steps {
                dir('/home/saikrishna/test4/') {          
                    git branch: 'stage',credentialsId: '', url: 'https://github.com/ct-VenkataSaiKrishna/gitTags.git'
                }
            }
        }       
    }
}
