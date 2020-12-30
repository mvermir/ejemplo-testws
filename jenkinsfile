pipeline {
    agent any

    stages {
        stage('Test WS') {
            steps {
                sh "newman run Test-WebServices.postman_collection.json"
            }
        }
    }
}
