pipeline {
    agent any
    
    stages {
        stage ('Instalar dependencias de Nodejs'){
            steps{
                sh "npm install"
            }
        }
        stage ('Testing de Nodejs'){
            steps{
                sh "npm test"
            }
    }
} 