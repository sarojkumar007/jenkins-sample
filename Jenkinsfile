pipeline{
  agent any
  
  stages{
    stage('clone'){
      steps{
        git 'https://github.com/sarojkumar007/jenkins-sample.git'
      }
    }
    stage('building job'){
      steps{
        build 'job2'
      }
    }
    stage('Testing'){
      steps{
        echo 'Testing ...'
      }
    }
  }
}
