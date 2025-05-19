pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/username/repo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
                // Add your build command like: sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
                // Add your test command here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Add your deploy steps here
            }
        }
    }
}
