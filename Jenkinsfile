pipeline{
    agent any
    
    stages{
        stage("Install Dependencies"){
            steps{
                bat 'npm install'
            }
            
        }

        stage("Run testing"){
            step{
                bat 'npm run test'
            }

        }
    }
}