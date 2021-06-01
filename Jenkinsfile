pipeline{
    agent any
    stages{
        stage("Run test"){
            steps{
                sh "docker-compose up --no-color"
            }
        }
        stage("Bring Grid Down"){
            steps{
                sh "docker-compose down"
            }
        }
    }
}