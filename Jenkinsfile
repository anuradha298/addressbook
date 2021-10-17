pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                maven compile
            }
        }
        stage('test') {
            steps { 
                maven test
            }
        }
        stage('package') {
            steps { 
                maven package
            }
        }
    }
}
