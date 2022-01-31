pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                // Get some code from a GitHub repository
                sh "rm -rf *"
                sh "git clone https://github.com/val81/devos.git"
                
            }
        }
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                sh "cd devos && javac Main.java"
            }
        }
        stage('Run') {
            steps {
                // Get some code from a GitHub repository
                sh "cd devos && java Main"
            }
        }
    }
}
