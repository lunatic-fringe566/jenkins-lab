pipeline{
  agent any
  stages{
    stage("Build"){
      steps {
        echo 'running code'
        sh 'javac labexam.java'
        sh 'java labexam'
      }
    }
   stage("Test"){
      steps{
        echo 'testing .....'
      }
    }
   stage("Deployment"){
      steps{
        echo 'deploying .....'
      }
    }
  }
}
