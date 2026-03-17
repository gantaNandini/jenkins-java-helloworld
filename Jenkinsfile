pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/gantaNandini/jenkins-java-helloworld.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'javac Main.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Main'
            }
        }
    }
}
