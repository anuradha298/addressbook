pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
               
                 sh 'mvn test'
            }
        }
        stage('test') {
            steps { 
                sh 'mvn test-compile'
            }
        }
        stage('package') {
            steps { 
                sh 'mvn package'
                   
            }
     
        }
    

    }
}
