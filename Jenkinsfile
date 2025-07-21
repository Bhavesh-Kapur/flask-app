pipeline{
  agent any
  environment{
    VENV = 'venv'
  }
  stages{
    stage('Checkout git'){
      steps{
        git branch: 'main', url: 'https://github.com/Bhavesh-Kapur/flask-app.git'
      }
    }
  }
}
