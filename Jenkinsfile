pipeline{
  agent any
  stages{
    stage('Build'){
      when{
        //buildingTag()
        tag "release/*"
        tag "1.0"
      }
      steps{
        echo "Building tag"
      }
    }
  }
}
