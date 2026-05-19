pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                // Actual git checkout command usually goes here, e.g., checkout scm
            }
        }
        
        stage('Build') {
            steps {
                echo 'Building the project...'
                // e.g., sh 'npm run build' or sh './gradlew build'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // e.g., sh 'npm test' or sh './gradlew test'
            }
        }

        stage('Run Application') {
            steps {
                echo 'Launching the application...'
                // Choose the command that matches your tech stack:
                
                // Example for Node.js:
                // sh 'npm start'
                
                // Example for Python:
                // sh 'python app.py'
                
                // Example for a Java Jar:
                // sh 'java -jar build/libs/app.jar'
            }
        }
    }
}
