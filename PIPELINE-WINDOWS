pipeline {
    agent any

    stages {
        stage('Get hostname') {
            steps {
                bat 'wmic computersystem get name'
            }
        }
		stage('Get ENV') {
            steps {
                bat 'echo %PATH%'
            }
        }
		stage('get dir') {
            steps {
                bat 'dir'
            }
        }
		stage('install git') {
            steps {
                bat 'cd "C:/Users/nso/Downloads/"'
            }
        }
		stage('get git version ') {
            steps {
                bat 'git version'
            }
        }
    }
}
