pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'nodejs-app' }      
      steps {
        container('nodejs') {
          echo 'Hello World!'   // on the controller
          sh 'java -version' // on the agent
        }
      }
    }
  }
}
