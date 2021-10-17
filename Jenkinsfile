pipeline {
    agent any
    tools{
         Maven "MAVEN_HOME"
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
