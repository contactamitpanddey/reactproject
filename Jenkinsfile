pipeline {
    agent { label 'agentlinux' }

    stages {
        stage('check version') {
            steps {
                sh "npm --version"
                sh "node --version"
            }
        
        }
    }
}
