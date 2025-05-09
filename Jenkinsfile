pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/ayesha-muskan-2114/Java_Test_Code.git'
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
