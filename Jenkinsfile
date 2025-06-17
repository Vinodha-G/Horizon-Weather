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
      echo "Skipping deployment as deployment.yaml is not yet added"
      // sh 'oc apply -f deployment.yaml'
    }
  }
}

    }
}
