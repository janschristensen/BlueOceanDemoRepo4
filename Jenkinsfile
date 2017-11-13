pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        echo 'Hello from Clone'
      }
    }
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Hello from Test'
          }
        }
        stage('Integrationstest') {
          steps {
            echo 'Hello from integrationstest'
          }
        }
      }
    }
  }
}