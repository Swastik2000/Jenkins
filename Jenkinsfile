pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh '''
                pwd
                ls
                mkdir -p sa{1..10}/{1,2,3}

                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh '''
                pwd

                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                ls
            }
        }
    }
}