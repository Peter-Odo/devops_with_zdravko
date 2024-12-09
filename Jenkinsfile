pipeline {
    agent any

    stages {
        stage('Start Automation Script on Dev Branch') {
            steps {
                echo 'Starting the automation script....'
            }
        }
        stage('Install Dependencies on Dev Branch') {
            steps {
                echo 'npm install'
            }
        }
        stage('Production Build on Dev Branch') {
            steps {
                echo 'npm run build'
            }
        }
         stage('Lint Build on Dev Branch') {
            steps {
                echo 'npm run lint'
            }
        }
         stage('Start Stage Deploy on Dev Branch') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Staging Environment on Dev Branch') {
            steps {
                echo 'Deployed to staging.devops.com 🎉'
            }
        }
    }
}