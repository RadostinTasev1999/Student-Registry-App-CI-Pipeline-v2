pipeline{
    agent any

    stages{
       stage("Install Dependencies"){
           steps{
               bat 'npm install'
           }       
       }
       stage("Run UI tests"){
            steps{
                bat 'npm test'
            }
       }
    }
   
}