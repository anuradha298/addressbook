pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                cmd_exec('mvn compile')
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
