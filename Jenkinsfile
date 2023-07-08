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
                ls -al

                '''
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sh '''
                pwd
                ls

                '''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh '''
                pwd
                ls

                '''
            }
        }
    }
}