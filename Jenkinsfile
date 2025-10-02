pipeline {
    agent any // Run on any available agent

    stages {
        stage('Checkout') {
            steps {
                // This automatically checks out the correct branch
                // that this pipeline job is configured to use.
                checkout scm
                echo 'Code checked out ho gya.'
            }
        }

        stage('Build') {
            steps {
                // Add your build command here
                // Example for Node.js: sh 'npm install'
                // Example for Maven:   sh 'mvn clean package'
                echo 'project ban rha hai...'
            }
        }

        stage('Test') {
            steps {
                // Add your test command here
                // Example for Node.js: sh 'npm test'
                // Example for Maven:   sh 'mvn test'
                echo 'test ho rahe hai...'
            }
        }
    }
}
