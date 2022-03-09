pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                javac HelloWorld.java
                java HelloWorld
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    
    post {
        always{
             echo 'post always....'
        }
    }
}
