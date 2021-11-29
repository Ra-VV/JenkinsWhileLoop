pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                expression {
                    BRANCH_NAME == 'prod'
                }
            }
            steps {
                echo 'Building..'
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
