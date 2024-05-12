pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                sh 'python --version'
            }
        }
         stage('build') {
          steps {
               sh 'python hello.py'
          }
       }
   }
}
