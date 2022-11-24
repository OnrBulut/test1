pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                slackSend color: "good", message: "Message from Jenkins Pipeline"
            }
        }
    }
}
