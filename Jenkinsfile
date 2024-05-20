pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                echo "Testing"
                sh 'python3 --version'
            }
        }
         stage('build') {
          steps {
                  echo "Buiilding"
                  sh 'python3 hello.py'
          }
       }
   }
}
