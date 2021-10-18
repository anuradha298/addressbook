pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                
                bat '''  ECHO Hello World  '''
                bat 'cd C:\\Users\\HP\\addressbook\\'
                mvn build
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
