pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        nodejs('Node'){
          echo 'Building Application.....'
          cmd 'npm install'
        }
      }
    }
  }
}
