pipeline {
    agent any

    stages {
           stage("Build"){
            steps{
                dir("Nishanth"){
                    sh "mvn -f Maven-Deep-Learning/pom.xml -U -DSkipTests clean package"
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
