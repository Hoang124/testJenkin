pipeline {
    agent any
    tools{
        nodejs '19.1.0'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'echo xin chao'
                sh 'npm install' 
            }   
        }
        stage('test') { 
            steps {
                sh 'echo test'
            }   
        }
        stage('delivery'){
            steps{
                sh 'npm run dev'
            }
        }
    }
}