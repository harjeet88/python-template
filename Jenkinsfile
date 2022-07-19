pipeline {
    agent any
    stages {
        stage('setup') {
            steps {
                sh 'echo "set up"'
                sh 'python3 --version'
            }
        }
        stage('testing') {
            withPythonEnv('python3') {
                sh 'pip install pytest'
                sh 'pytest mytest.py'
            }
       }
       
    }
}
