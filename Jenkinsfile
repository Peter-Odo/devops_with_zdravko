pipeline {
    agent any

    stages {
        stage('Start Automation Script on Fix two') {
            steps {
                echo 'Starting the automation script....'
            }
        }
        stage('Install Dependencies on Fix two') {
            steps {
                echo 'npm install'
            }
        }
        stage('Production Build on Fix two') {
            steps {
                echo 'npm run build'
            }
        }
         stage('Lint Build on Fix two') {
            steps {
                echo 'npm run lint'
            }
        }
         stage('Start Stage Deploy on Fix two') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Staging Environment on Fix two') {
            steps {
                echo 'Deployed to staging.devops.com 🎉'
            }
        }
    }
}