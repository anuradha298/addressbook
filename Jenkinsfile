pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                cmd 'mvn compile'
            }
        }
        stage('test') {
            steps { 
                cmd 'mvn test'
            }
        }
        stage('package') {
            steps { 
                cmd 'mvn package'
            }
        }
    }
}
