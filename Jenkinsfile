pipeline {
    agent any 
    stages {
         stage('test') {
            steps {
                sh 'python3 --version'
            }
        stage('build') {
          steps {
            sh 'python3 hello.py'
          }
       }
   }
}
