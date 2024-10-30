pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
                git "https://github.com/devops0014/multibranch-javaapp.git"
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}

