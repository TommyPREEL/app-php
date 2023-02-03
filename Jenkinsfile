pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'curl http://formation.ludovic.tech:8089/create_db.php'
            }
        }
    }
}
