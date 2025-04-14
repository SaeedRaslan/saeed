pipeline {
    agent any

    stages {
        stage('Clone and Run Script') {
            steps {
                sh 'chmod +x ./script.sh'
                sh './script.sh'
            }
        }
    }
}
