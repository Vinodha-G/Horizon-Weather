pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Deploy to OpenShift') {
            steps {
                script {
                    sh 'oc whoami'
                    sh 'oc apply -f deployment.yaml'
                }
            }
        }
    }
}
