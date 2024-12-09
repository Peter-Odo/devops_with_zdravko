pipeline {
    agent any

    stages {
        stage('Start Automation Script on Master') {
            steps {
                echo 'Starting the automation script....'
            }
        }
        stage('Install Dependencies on Master') {
            steps {
                echo 'npm install'
            }
        }
        stage('Production Build on Master') {
            steps {
                echo 'npm run build'
            }
        }
         stage('Lint Build on Master') {
            steps {
                echo 'npm run lint'
            }
        }
         stage('Start Stage Deploy on Master') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Staging Environment on Master') {
            steps {
                echo 'Deployed to staging.devops.com 🎉'
            }
        }
    }
}