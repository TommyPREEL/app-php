pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'curl localhost:9000/create_db'
            }
        }
    }
}
