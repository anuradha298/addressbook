pipeline {
    agent any
    tools{
         Maven "3.8.2"
    }
    stages {
        stage('Compile') {
            steps { 
                bat '''  ECHO Hello World  '''
            }
        }
        stage('test') {
            steps { 
              
                bat "mvn test"
            }
        }
        stage('package') {
            steps { 
               bat '''  ECHO Hello World  '''
                   
            }
     
        }
    

    }
}
