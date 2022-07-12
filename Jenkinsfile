pipeline {
  agent any 
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello World!'   // on the controller
        sh 'java -version' // on the agent
      }
    }
  }
}
