pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'no need to hurry'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
