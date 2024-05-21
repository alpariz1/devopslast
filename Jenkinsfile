pipeline {
    agent any
    environment {
        // Use DockerHub credentials
        DOCKERHUB_CREDENTIALS = credentials('48499f28-75b4-47da-a751-d356f9a7ae4c')
    }
    stages {
        stage('Pull the project from GitHub') {
            steps {
                echo 'Getting project from GitHub'
                git 'https://github.com/alpariz1/devopslast' // Missing parenthesis
            }
        }
        stage('Building JAR') {
            steps {
                echo 'Start building JAR file'
                sh 'gradle clean bootJar' // Missing parenthesis
            }
        }
        stage('Create the Docker image') {
            steps {
                echo 'Image has been built' // Missing parenthesis
                sh 'docker build -t alpariz/app .' // Missing parenthesis
            }
        }
        stage('Login to DockerHub') {
            steps {
                // Pipe DockerHub password securely
                sh "echo \$DOCKERHUB_CREDENTIALS_PSW | docker login -u \$DOCKERHUB_CREDENTIALS_USR --password-stdin" // Corrected syntax
                echo 'Logged in'
            }
        }
        stage('Push the image to DockerHub') {
            steps {
                sh 'docker push alpariz/app123' // Missing parenthesis
                echo 'Image is pushed' // Missing parenthesis
            }
        }
    }
}