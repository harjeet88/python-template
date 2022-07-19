pipeline {
    agent any
    stages {
        stage('setup') {
            steps {
                sh 'echo "set up"'
          }
      }
        stage('testing') {
            steps {
                sh 'pip install pytest'
                sh 'pytest mytest.py'
            }
       }
       
    }
}
