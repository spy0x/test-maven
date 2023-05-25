pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '0b9afb25-7825-4335-b11d-3c887646b97b', url: 'https://github.com/spy0x/test-maven'
            }
        }
    }
}
