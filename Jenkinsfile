pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/jenkinsci/jenkins.git', branch: 'main'
            }
        }

        stage('Compile Java') {
            steps {
                sh 'javac Test.java'
            }
        }

        stage('Run Java Program') {
            steps {
                sh 'java Test'
            }
        }
    }
}
