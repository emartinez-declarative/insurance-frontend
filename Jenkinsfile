pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'nodejs-app' }      
      steps {
        echo 'Hello World!'   // on the controller
        sh 'java -version' // on the agent
      }
    }
  }
}
