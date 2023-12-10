pipeline{
    agent any
    stages{
        stage('build'){
            steps{
                echo 'Etapa build no diponible'
            }
        }
        stage('Test'){
            steps{
                echo 'etapa test no disponible'
            }
        }

        stage('Deploy') {
            steps{
                sh 'docker-compose down'
                sh 'docker-compose up -d --build'
            }
        }
    }
}