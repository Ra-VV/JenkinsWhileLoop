pipeline {
    agent any

    stages {
        stage('Build_Stage') {
            when {
                expression {
                    BRANCH_NAME == 'prod'
                }
            }
            steps {
                echo 'Building..'
            }
        }
        stage('Test_Stage') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy_Stage') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
