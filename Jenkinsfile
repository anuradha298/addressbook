pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                
                bat '''  ECHO Hello World  '''
                bat 'start cmd.exe'
                cmd_exec ('C:\Users\HP\addressbook')
                cmd_exec ('echo hello8')
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
