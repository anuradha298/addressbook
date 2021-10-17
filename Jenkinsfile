pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                bat '''  ECHO Hello World  '''
            }
        }
        stage('test') {
            steps { 
                bat '''  maven test  '''
            }
        }
        stage('package') {
            steps { 
               bat '''  ECHO Hello World  '''
                   
            }
        }
    }
}
