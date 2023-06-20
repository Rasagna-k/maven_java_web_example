pipeline{
  agent any
  stages{
    stage('Bulid') {
      steps{
        sh 'mvn clean install'
          echo 'building the project'
    }
    }
     stage('test') {
       steps{
          echo 'testing the project '
       }
    }
     stage('deploy') {
       steps{
          echo 'deploying the project '
       }
    }
  }
}
