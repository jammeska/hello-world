pipeline {
    agent any

    stages {
        stage('git checkout') {
            steps {
                git 'https://github.com/jammeska/hello-world.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}
