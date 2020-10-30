pipeline {
  agent any
  stages {
    stage('make python script'){
      steps {
      sh "touch helloworld.py"
      
      }
    }
    stage('run python script'){
      steps{
        python3 helloworld.py
      }
    }
  }
}
