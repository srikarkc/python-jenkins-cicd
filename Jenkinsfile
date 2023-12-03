pipeline {
    agent any

    stages {
        stage('Clean working directory') {
            steps {
                sh 'rm -rf python-jenkins-cicd.git'
            }
        }
        stage('Pull from GitHub') {
            steps {
                sh 'git clone https://github.com/srikarkc/python-jenkins-cicd.git'
                //sh 'ls'
            }
        }
        stage('Running the Python file') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
