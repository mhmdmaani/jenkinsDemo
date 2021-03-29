pipeline{
     agent any
     tools{
         maven 'Maven'
     }
    stages{
        stage('build'){
            steps{
                echo 'Hello World'
                sh 'java -version'
                sh 'mvn clean compile'
            }
        }
    }
}