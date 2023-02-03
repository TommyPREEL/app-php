pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh 'curl http://localhost:9000/create_db.php'
            }
        }
    }
}
