pipeline {
    agent  any

    stages {
        stage("build image") {
            steps {
                script {
                    sh "docker build jenkins -t docker-in-jenkins"
                }
            }
        }
    }
}
