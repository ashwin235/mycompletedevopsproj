
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               
                echo 'Building..'
                sh 'echo "started coding" | wc '
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
