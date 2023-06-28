pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("Nishanth"){
                    sh "mvn -f pom.xml -U -DSkipTests clean package"
                }
            }
        }
        stage("Test"){
            steps{
                dir("NIshanth"){
                    sh "mvn -f pom.xml test"
                }
        }        
    }
}}
