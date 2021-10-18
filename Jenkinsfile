pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                
                bat '''  ECHO Hello World  '''
                bat 'start cmd.exe /c C://Users//HP//addressbook//mvn build'
                bat  ''' echo hello8 '''
                bat ''' mvn build '''
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
