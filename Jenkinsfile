pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building Maven Project'
                bat 'mvn clean install'
            }
        }
    }
}
