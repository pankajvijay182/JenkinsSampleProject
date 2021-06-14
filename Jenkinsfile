pipeline{
  
  stages{
    stage("Cleaning Stage"){
      steps{
      bat "mvn clean"
      }
    }
    stage("Testing Stage"){
      step{
      bat "mvn test"
      }
    }
    stage("Packaging Stage"){
      step{
      bat "mvn package"        
      }
    }    
}
  
  
  
  
  
  
}
