pipeline {
    agent any

    stages {
        stage('Clone repo') {
            steps {
                git branch: 'main', credentialsId: 'github-ssh', url: 'https://github.com/Sankalpa-it/CI-CD.git'
            }
        }
         stage('date') {
            steps {
                sh 'date'
            }
        }
         stage('ls') {
            steps {
                sh 'ls'
            }
        }
         stage('uptime') {
            steps {
                sh 'uptime'
            }
        }
         stage('Disk size') {
            steps {
                sh 'df -h'
            }
        }
    }
}
