pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/user/repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building App'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing App'
            }
        }
    }
}
