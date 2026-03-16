pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/pingvinoth25-git/jenkins-demo-project-16032026'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build completed successfully"'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp -r * /var/www/html/'
            }
        }

    }
}
