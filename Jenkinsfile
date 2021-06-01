pipeline{
    agent any
    stages{
        stage("Run test"){
            steps{
                sh "docker-compose up"
            }
        }
        stage("Bring Grid Down"){
            steps{
                sh "docker-compose down"
            }
        }
    }
}