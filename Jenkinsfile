pipeline{  
    agent any
    stages {
        stage('Test'){
        steps{
            script{
                sh 'npm run test'
            } 
        }   
        

        stage('Build'){
           steps{
              script{
                sh 'npm install'
              } 
           }   
        }
    }
}