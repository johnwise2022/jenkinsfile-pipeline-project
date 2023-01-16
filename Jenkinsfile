pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'bitti nidaları altında'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
