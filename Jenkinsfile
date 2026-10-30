pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Source code is available'
            }
        }
        stage('Build') {
            steps {
                echo 'Preparing project'
            }
        }
        stage('Test') {
    steps {
        echo "Running tests successfully for branch ${env.BRANCH_NAME}"
    }
}
    }
    post {
        success {
            echo 'Pipeline completed successfully'
        }
        failure {
            echo 'Pipeline failed. Check the logs'
        }
    }
}
