pipeline {
    agent any

    stages {
        stage('DownloadCode') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/zaheer800/JenkinsSample.git'
            }
        }
        stage('NPMInstall') {
            steps {
                // Get some code from a GitHub repository
                bat 'npm install'
            }
        }
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                bat 'npm run ng build'
            }
        }
    }
}