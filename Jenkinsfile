pipeline {
    agent any
       stages {
        stage('Compile') {
            steps { 
                 bat 'cd..'
                 bat 'mvn compile'
            }
        }
        stage('test') {
            steps { 
                bat 'mvn build'
            }
        }
        stage('package') {
            steps { 
                bat 'mvn package'
                   
            }
     
        }
    

    }
}
