pipeline {
    agent any
    stages {
        stage('Run Script') {
            steps {
                sh 'chmod +x test.sh'
                sh './test.sh'
            }
        }
    }
}
