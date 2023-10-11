pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Git clone') {
            steps {
                git credentialsId: harshadatarge 'jenkins-master-server', url: 'https://github.com/wakaleo/game-of-life'
            }
        }
    }
}
