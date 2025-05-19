pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Ayesha-Muskan-2114/Java_Test_Code.git'
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
