pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'SCM nin kontrol edilmesi, Schedule testi 5555555'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo SCM nin kontrol edilmesi, Schedule testi'
            }
        }
        stage('run2') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python --version'
                sh 'python pipeline.py'
            }
        }
    }
}
