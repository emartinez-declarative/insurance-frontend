pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'nodejs-app' }      
      steps {
        sh 'java -version' // on the agent
        container('nodejs') {
          echo 'Hello World!'   // on the controller
          sh 'node --version'
        }
      }
    }
  }
}
