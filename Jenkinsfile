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
                bat 'C:/Users/nso/Downloads/Git-2.29.2.2-64-bit.exe /INSTALL /SP /NQ /NOREBOOT /VERYSILENT'
            }
        }
		stage('get git version ') {
            steps {
                bat 'git version'
            }
        }
    }
}
