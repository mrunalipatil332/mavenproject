pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "/user/share/maven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "/user/share/maven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "/user/share/maven/bin/mvn package"
            }
        }
    }
}
