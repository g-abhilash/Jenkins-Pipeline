pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                bat "/opt/maven/bin/mvn clean"
            }
        }
        stage('--test--') {
            steps {
                bat "/opt/maven/bin/mvn test"
            }
        }
        stage('--package--') {
            steps {
                bat "/opt/maven/bin/mvn package"
            }
        }
    }
}
