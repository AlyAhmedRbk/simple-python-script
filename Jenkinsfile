pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                bat 'python --version'
            }
        }
         stage('build') {
          steps {
            bat 'python hello.py'
          }
       }
   }
}
