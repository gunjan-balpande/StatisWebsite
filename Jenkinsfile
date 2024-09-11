pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/gunjan-balpande/StatisWebsite.git'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sudo cp -r * /var/www/html/'
            }
        }
    }
}
