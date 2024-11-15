pipeline{
agent any
stages{
  stage('Checkout'){
    steps{
          echo 'Pulling code from git'
          git 'https://github.com/Nagashreer6515/CypressNodejs.git'
     }
}
  stage('Build'){
    steps{
          echo 'Running the tests'
          bat 'npx cypress run'
     }
}
  stage('Finishing'){
  steps{
    echo 'Finishing is Done'
   }
}
}
}
