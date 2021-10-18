pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                
                bat '''  ECHO Hello World  '''
                bat 'start cmd.exe'
                bat ''' C://Users//HP//addressbook '''
                bat  ''' echo hello8 '''
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
