pipeline {
    agent any 

    tools {nodejs "node"}

    stages{
        stage('Build') {
            steps {
                bat 'npm install'
            }
        }
        stage('Deploy'){
            steps{
                bat 'npm run deploy'
            }
        }
    }
}
