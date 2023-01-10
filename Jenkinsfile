pipeline {
    agent any
    tools {
        jdk "jdk17-0-5"
    }
        stages{
        stage("Build"){
            steps {
                git 'https://github.com/babacardiiop/demo-retourdevacances.git'
                sh "chmod +x ./gradlew"
                sh "./gradlew build"
                
            }
        }
   }}
