pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                echo "Testing"
                sh 'python --version'
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
