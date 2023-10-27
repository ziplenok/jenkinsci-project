pipeline {
    agent any
    stages {

        stage("mvn build") {
            steps {
                script {
                    sh "mvn clean package"
                }
            }
        }
    }
}
