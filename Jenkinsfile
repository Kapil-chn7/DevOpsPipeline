pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Placeholder build step
                echo 'Its oops Building...okay its building this is the finallll'
                git branch: 'main', credentialsId: 'GithubToken', url: 'https://github.com/Kapil-chn7/DevOpsPipeline.git'
            }
        }
        stage('Test') {
            steps {
                // Placeholder test step
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Placeholder deploy step
                echo 'Deploying...'
            }
        }
    }
}
