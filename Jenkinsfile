pipeline {
    agent any
    tools{
        nodejs '19.1.0'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'cd api'
                sh 'npm install' 
            }   
        }
    }
}