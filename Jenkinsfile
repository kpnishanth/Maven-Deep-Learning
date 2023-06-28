pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("Nishanth"){
                    sh "mvn -U clean package"
                }
            }
        }
        stage("Test"){
            steps{
                dir("NIshanth"){
                    sh "mvn test"
                }
        }        
    }
}}
