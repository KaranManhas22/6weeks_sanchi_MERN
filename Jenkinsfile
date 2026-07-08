pipeline {
    agent any 
    tools {nodejs 'Mynode'}

    stages {
        stage('first dtep') {
            steps {
                echo 'clone'
                git url: 'https://github.com/duggalvaibhav8-beep/frontseedly.git' , branch: 'main'
            }
        }
        
        
        stage('install') {
            steps {
                echo 'pacakages'
                bat 'npm install'
            }
        }
        
        
        stage('startind') {
            steps {
                bat 'npm run dev -- --host'
            }
        }
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
    }
}