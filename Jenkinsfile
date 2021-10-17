pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                bat '''mvn build'''
            }
        }
        stage('test') {
            steps { 
               bat '''mvn test'''
            }
        }
        stage('package') {
            steps { 
               bat '''mvn package'''
            }
        }
    }
}
