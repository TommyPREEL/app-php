pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'curl http://formation.ludovic.tech:9000/create_db.php'
            }
        }
    }
}
