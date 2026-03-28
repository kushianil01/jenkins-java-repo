pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'Compiling Java code'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Java tests'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging JAR'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Java app'
            }
        }
    }
}
