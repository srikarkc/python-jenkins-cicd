pipeline {
    agent any

    stages {
        stage('Pull from GitHub') {
            steps {
                sh 'git clone https://github.com/srikarkc/python-jenkins-cicd.git'
                sh 'ls'
            }
        }
    }
}
