pipeline{
    agent any
    stages{
        stage('validate'){
            steps{
                bat "mvn validate"
            }
        }        
        stage('maven compile'){
            steps{
                bat "mvn validate"
            }
        }
        stage('test'){
            steps{
                bat "mvn clean verify"
            }
        }
    }
}
