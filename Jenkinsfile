pipeline{
    agent any
    tools{
        maven 'maven'
    }
    
    stages{
        stage('compile'){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
