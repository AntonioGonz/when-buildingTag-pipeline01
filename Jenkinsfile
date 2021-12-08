pipeline{
  agent any
  stages{
    stage('Build'){
      when{
        //buildingTag()
        tag "1.0"
      }
      steps{
        echo "Building tag"
      }
    }
  }
}
