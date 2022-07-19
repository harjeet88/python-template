pipeline {
    agent any
    stages {
        stage('setup') {
            steps {
                sh 'echo "set up"'
                sh 'apt-get update'
                sh 'apt-get install -y 3.7.11'
            }
        }
    }
}
