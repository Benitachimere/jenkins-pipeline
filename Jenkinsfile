pipeline{
  
  agent any
  
  tools {
  maven 'Maven'
}

  stages{
    stage("Git Checkout"){
      steps{
         git 'https://github.com/Divyabd/Jenkins-Full-Course-on-aws-Linux.git'
      }
    }
    
    stage ("mvn version check "){
      steps{
        sh 'mvn --version'
      }
    }
    
  }
}
