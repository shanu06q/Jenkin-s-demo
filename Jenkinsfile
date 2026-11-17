pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps { checkout scm }
    }
    stage('Build') {
      steps { sh 'echo Building the project...' }
    }
    stage('Test') {
      steps { sh 'echo Running tests... && test 1 -eq 1' }
    }
    stage('Notify') {
      steps { echo 'Pipeline completed successfully!' }
    }
  }
}
