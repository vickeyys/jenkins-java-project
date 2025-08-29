
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/vickeyys/jenkins-java-project.git'
            }
        }

        stage('Test') {
            steps {
                echo 'Test run on dev branch'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy to the dev cluster'
            }
        }
    }
}
