pipeline{
  agent any 
  stages{
    stage('Bomanai'){
      steps{
         sh '''pip install --no-cache-dir --upgrade boman-cli
             ~/.local/bin/boman-cli -a run -cicd jenkins'''
      }
    }
  }
}
