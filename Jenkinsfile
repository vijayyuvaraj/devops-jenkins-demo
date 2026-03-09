pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {git branch: 'main', url: 'https://github.com/vijayyuvaraj/devops-jenkins-demo.git'
            }
        }

        stage('Build Stage') {
            steps {
                echo "Build completed successfully"
            }
        }

        stage('Test Stage') {
            steps {
                echo "Test executed"
            }
        }
    }
}
