pipeline{
  agent any
  
  stages {
    stage("Build") {
      steps {
          sh -x $WORKSPACE/execute.sh
      }
    }
  }
}
