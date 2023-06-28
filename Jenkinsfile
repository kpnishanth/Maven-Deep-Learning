pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                  sh "mvn -f pom.xml -U -DSkipTests clean package"
        
            }
        }
        stage("Test"){
            steps{
                           sh "mvn -f pom.xml test"
                
        }        
    }
}}
