pipeline {
    agent any

    environment {
        NEW_VERSION = '1.3.0'
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building Project'
                echo "Building version ${NEW_VERSION}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing Project'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying Project'
            }
        }
    }

    post {
        always {
            echo 'Post build condition running'
        }
    }
}
