pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run integration Tests') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}