pipeline{
  agent any 
  stages{
    stage("build"){
      steps{
        bat "mvn package"
      }
    }
    stage("deploy"){
      steps{
        echo "deployed"
      }
    }
  }
}
