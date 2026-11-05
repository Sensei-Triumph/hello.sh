pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh './hello.sh'
            }
        }
    }

    post {
        success { echo 'Pipeline finished successfully.' }
        failure { echo 'Something went wrong.' }
    }
}