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
                echo 'npm install'
            }
        }
        stage('Production Build') {
            steps {
                echo 'npm run build'
            }
        }
         stage('Lint Build') {
            steps {
                echo 'npm run lint'
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