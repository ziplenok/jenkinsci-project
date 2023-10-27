pipeline {
    agent any
    tools {
        maven "localMaven"
        jdk "Java9"
    }
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
