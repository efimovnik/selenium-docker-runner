pipeline{
    agent any

    stages{
        stage('Run Test'){
            steps{
                sh "docker-compose up"
            }
        }
        stage('Bring Grid Down'){
            steps{
                echo "docker-compose down"
            }
        }
    }
}