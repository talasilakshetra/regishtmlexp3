pipeline{
  agent any
  stage('Checkout SCM') {
            steps {
                checkout scm
            }
        }
  stages{
    stage(Build){
      steps{
        echo 'building...'
      }
    }
    stage(Test){
      steps{
        echo 'testing...'
      }
    }
    stage(Deploy){
      steps{
        echo 'deploying....'
      }
    }
  }
}
