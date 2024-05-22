 pipeline {
    agent any
    environment {
        GIT_CREDENTIALS = credentials('98e27194-d578-43bd-93fb-773de2f1e910')
        DOCKERHUB_TOKEN = credentials('dockerpat')
        //KUBECONFIG = credentials('kubeconfig_id')
    }
    stages {
        stage('Pull the project from GitHub') {
            steps {
                echo 'Getting project from GitHub'
                git branch: 'main', credentialsId: '98e27194-d578-43bd-93fb-773de2f1e910', url: 'https://github.com/alpariz1/devopslast.git'
                bat './gradlew clean bootJar'
            }
        }
        
        stage('Create the Docker image') {
            steps {
                echo 'Image has been built'
                bat 'docker build -t alpariz/app:latest .'
            }
        }
        
        stage('Login to DockerHub') {
            steps {
                withCredentials([string(credentialsId: 'dockerpat', variable: 'DOCKERHUB_TOKEN')]) {
                    echo "Logging in to DockerHub"
                    bat """
                    docker login -u alpariz -p %DOCKERHUB_TOKEN%
                    """
                    echo 'Logged in'
                }
            }
        }
        
        stage('Push the image to DockerHub') {
            steps {
                bat 'docker push alpariz/app:latest'
                echo 'Image is pushed'
            }
        }
    }
     
}
