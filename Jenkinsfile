pipeline {
  agent { docker { image 'php' } }
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'php --version'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
