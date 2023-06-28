pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("SpringMVCTest"){
                    sh "mvn clean install"
                }
            }
        }
        stage("Test"){
            steps{
                dir("SpringMVCTest"){
                    sh "mvn test"
                }
        }        
    }
}}
