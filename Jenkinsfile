pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout Stage: Cloning the repository...'
                git url: 'https://github.com/repoTest/JenkinsTest.git', branch: 'main', credentialsId: 'github-credentials-id'
            }
        }
        stage('Build') {
            steps {
                echo 'Build Stage: Building the project...'
                // Ajoutez vos commandes de build ici, par exemple :
                // sh 'make build'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Stage: Running tests...'
                // Ajoutez vos commandes de test ici, par exemple :
                // sh 'make test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Stage: Deploying the application...'
                // Ajoutez vos commandes de déploiement ici, par exemple :
                // sh 'make deploy'
            }
        }
    }
}
