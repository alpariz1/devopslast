pipeline {
    agent any
    environment {
        GIT_CREDENTIALS = credentials('98e27194-d578-43bd-93fb-773de2f1e910')
        DOCKERHUB_TOKEN = credentials('dockerpat')
       // KUBECONFIG = credentials('kubeconfig_id')
        //DOCKER_CLIENT_TIMEOUT = '300' // Set to 300 seconds
        //COMPOSE_HTTP_TIMEOUT = '300'  // Set to 300 seconds
    }
    stages {a
        stage('Pull the project from GitHub') {
            steps {
                echo 'Getting project from GitHub'
                git branch: 'main', credentialsId: '98e27194-d578-43bd-93fb-773de2f1e910', url: 'https://github.com/alpariz1/devopslast.git'
                bat 'chmod +x gradlew'
                bat './gradlew clean bootJar'
            }
        }
        
        stage('Create the Docker image') {
            steps {
                echo 'Image has been built'
                bat 'docker build -t alpariz/app:latest . --progress=plain --no-cache'
            }
        }
        
        stage('Login to DockerHub') {
            steps {
                withCredentials([string(credentialsId: 'dockerpat', variable: 'DOCKERHUB_TOKEN')]) {
                    echo "Logging in to DockerHub"
                    bat """
                    echo %DOCKERHUB_TOKEN% | docker login -u alpariz --password-stdin
                    """
                    echo 'Logged in'
                }
            }
        }
        
        stage('Push the image to DockerHub') {
            steps {
                bat 'docker push alpariz/app:latest --debug'
                echo 'Image is pushed'
            }
        }
        
       stage('Pull the image from DockerHub') {
            steps {
                echo 'Pulling Docker image from DockerHub to local'
                bat 'docker pull alpariz/app:latest'
                echo 'Image is pulled'
            }
        }
}
