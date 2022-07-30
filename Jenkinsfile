pipeline{
    agent any
    stages{
        stage('Git clone'){
            steps{
                bat "mvn validate"
            }
        }        
        stage('maven compile'){
            steps{
                bat "mvn compile"
            }
        }
        stage('test'){
            steps{
                bat "mvn test"
            }
        }
    }
}
