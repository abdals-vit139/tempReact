pipeline{
    agent any
    stages{
        stage('Clone repo')
        {
            steps{
                git branch:'main',url:'https://github.com/abdals-vit139/tempReact.git'
            }
        }
        stage('install Dependencies')
        {
            steps{
                sh 'npm install'
            }   
        }
       
        stage('Start application'){
            steps{
                sh 'npm start'
            }
        }
    }
}
