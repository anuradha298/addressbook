pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                
                echo ''' test '''
            }
        }
        stage('test') {
            steps { 
                bat 'mvn build'
            }
        }
        stage('package') {
            steps { 
               bat '''  ECHO Hello World  '''
                   
            }
     
        }
    

    }
}
