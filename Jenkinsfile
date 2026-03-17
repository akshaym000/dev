pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git:'https://github.com/akshaym000/dev.git',
        branch:'main'
      }
    }
    stage('Runscript'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
