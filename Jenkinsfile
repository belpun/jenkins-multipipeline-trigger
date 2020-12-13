pipeline {
    agent any
    stages {
        stage("build-and-deploy-dev") {
            when {
                branch "trigger"
            }
            steps {
                powershell "mvn clean test"
            }
        }
    }
}
