pipeline {
    agent any 
    stages {
        stage('test') {
            steps {
                echo "Testing"
                sh 'python3 --version'
                echo "This is my IP"
                curl -s ifconfig.co
                echo "This is my hostname"
                hostname -f
            }
        }
         stage('build') {
          steps {
                  echo "Buiilding"
                  sh 'python3 hello.py'
          }
       }
         stage('deploy') {
          steps {
                  echo "Deploying App..."
                  sh 'python3 app.py'
          }
       }
   }
}
