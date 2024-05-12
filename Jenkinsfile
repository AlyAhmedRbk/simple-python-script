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
                  bat 'python3.10 hello.py'
          }
       }
   }
}
