pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'curl http://localhost:8089/create_db'
            }
        }
    }
}
