pipeline{
    agent any 
    stages{
        stage("checkout"){
            steps{
                checkout scm
            }
        }
 
        stage ("version check"){
            steps{
                sh "node --version"
                sh "npm --version"
            }
        }
 

    }
}
