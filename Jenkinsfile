pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git url: 'https://github.com/nareshh49/aug1923.git'
                sh 'ls -lart'
                sh 'javac addition.java'
            }
        }
        stage('Run') {
            steps {
                sh 'ls -lsrt'
                sh 'java Addition'
            }
        }
    }
}


