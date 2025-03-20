pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'master', credentialsId: 'github credentials', url: 'https://github.com/sindhujash/assign_2.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}