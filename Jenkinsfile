pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                 bat 'cd addressbook_main'
                 bat 'mvn test'
            }
        }
        stage('test') {
            steps { 
                bat 'mvn test-compile'
            }
        }
        stage('package') {
            steps { 
                bat 'mvn package'
                   
            }
     
        }
    

    }
}
