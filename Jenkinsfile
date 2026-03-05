pipeline {
    agent any

    stages {
        stage('Checkout'){
            steps {
                git 'https://github.com/RiyanshOverlord/Deveops-practical'
            }}
        
         stage('Build'){
            steps {
                bat 'javac Hello.java'
            }}
            stage('exe'){
                steps{
                bat 'java Hello'
            }}
        }
    }


