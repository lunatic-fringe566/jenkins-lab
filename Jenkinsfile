pipeline{
  agent any
  stages{
    stage("Build"){
      steps {
        echo 'running code'
        sh 'javac semexam.java'
        sh 'java semexam'
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
