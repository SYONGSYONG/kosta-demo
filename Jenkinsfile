pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/SYONGSYONG/kosta-demo.git'
                sh "mvn clean package"
            }

        }
    }
}
