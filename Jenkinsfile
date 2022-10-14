pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Get code from a GitHub repository
                git url: 'https://github.com/Clement-Loth/jenkins-helloworld', branch: 'master'
            }
        }
    }
}