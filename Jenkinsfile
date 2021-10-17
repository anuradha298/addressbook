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
                cmd_exec('echo "Buils starting..."')
            }
        }
        stage('package') {
            steps { 
               bat '''  ECHO Hello World  '''
                   
            }
       def cmd_exec(command) {
       return bat(returnStdout: true, script: "${command}").trim()
        }
    }

    }
}
