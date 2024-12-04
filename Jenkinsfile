pipeline {
    agent any

    stages {
        stage('Start Automation Script') {
            steps {
                echo 'Starting the automation script....'
            }
        }
        stage('Install Dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Production Build') {
            steps {
                bat 'npm run build'
            }
        }
         stage('Lint Build') {
            steps {
                bat 'npm run lint'
            }
        }
         stage('Start Stage Deploy') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Staging Environment') {
            steps {
                echo 'Deployed to staging.devops.com 🎉'
            }
        }
    }
}