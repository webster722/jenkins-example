pipeline{
    agent any
    tools {
        jdk 'java'
        maven 'maven_3_6_1'
    }
    stages{
        stage('Java Check'){
            steps{
                sh 'java -version'
                sh 'mvn clean install'
            }
            
        }
    }
}