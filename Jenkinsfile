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
                bat "run_build_windows.bat"
                mvn test
            }
        }
        stage('package') {
            steps { 
               bat '''  ECHO Hello World  '''
                   
            }
     
        }
    

    }
}
