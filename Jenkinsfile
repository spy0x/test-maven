pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '66d7f5aa-49a4-49e6-8c3e-6ae6d665af70', url: 'https://github.com/spy0x/test-maven.git'
            }
        }
    }
}
