pipeline {
    agent any
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World from Jenkins!'
                echo 'This is my first CI/CD pipeline'
            }
        }
        stage('Checkout') {
            steps {
                echo 'YOO BOY CHECKING OUT'
                echo 'ab itni door a gye hain to chekout kar hi lete hain'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Your build commands will go here
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Your test commands will go here
            }
        }
    }
}