pipeline{
    agent any
    
    stages{
        stage("Install Dependencies"){
            steps{
                bat 'npm install'
            }
            
        }

        stage("Run testing"){
            steps{
                bat 'npm run test'
            }

        }
    }
}