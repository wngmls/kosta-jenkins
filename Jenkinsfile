pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git 'https://github.com/wngmls/kosta-jenkins.git'
                sh "mvn clean package"
            }

        }
    }
}
