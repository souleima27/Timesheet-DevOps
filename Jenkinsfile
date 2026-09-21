pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'master',
                    url: 'https://github.com/OnsBENSALAH/Timesheet-DevOps.git'
            }
        }

        stage('Compile') {
            steps {
                bat 'mvn compile'
            }
        }

    }
}