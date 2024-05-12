pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                echo "Testing"
                bat 'git --version'
            }
        }
         stage('build') {
          steps {
                  echo "Buiilding"
               sh 'python hello.py'
          }
       }
   }
}
