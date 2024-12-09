pipeline {
    agent any

    stages {
        stage('Start Automation Script on Fix Branch') {
            steps {
                echo 'Starting the automation script....'
            }
        }
        stage('Install Dependencies on Fix Branch') {
            steps {
                echo 'npm install'
            }
        }
        stage('Production Build on Fix Branch') {
            steps {
                echo 'npm run build'
            }
        }
         stage('Lint Build on Fix Branch') {
            steps {
                echo 'npm run lint'
            }
        }
         stage('Start Stage Deploy on Fix Branch') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Staging Environment on Fix Branch') {
            steps {
                echo 'Deployed to staging.devops.com 🎉'
            }
        }
    }
}