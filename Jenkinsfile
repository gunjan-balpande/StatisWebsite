pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/gunjan-balpande/StatisWebsite.git'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sudo cp -r Jenkinsfile index.html styles.css /var/www/html/'
            }
        }
    }
}
