pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("Nishanth"){
                    sh "mvn -U -DSkipTests clean package"
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
