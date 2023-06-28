pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("Nishanth"){
                    sh "mvn clean install"
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
