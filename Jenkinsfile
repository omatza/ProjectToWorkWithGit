pipeline {
    agent any

    stages {
        stage('Checkout') {

            steps {
               git 'https://github.com/omatza/ProjectToWorkWithGit.git'
            }
        }
        stage('Run') {
            steps {
                bat 'python main.py'
            }
        }

    }
}
