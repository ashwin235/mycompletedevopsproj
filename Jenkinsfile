
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               
                echo "code is Building.."
                sh " echo started coding |  cat >> file2.txt "
              sh '  touch  file1.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..is in progress'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying... '
            }
        }
    }
}
