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
                dir("C:\\users\\HP")
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
