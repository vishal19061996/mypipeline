pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'I am in dev phase'
                sh 'git --version'
                echo 'checked git version'
            }
        }
stage('test') {
            steps {
                echo 'I am in test phase'
                sh 'docker --version'
            }
        }
stage('prod') {
            steps {
                echo 'I am in prod phase'
                sh 'mvn -v'
            }
        }
    }
}
