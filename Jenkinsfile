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
                bat "mvn package"
            }
        }
        stage('test'){
            steps{
                bat "mvn clean install"
            }
        }
    }
}
