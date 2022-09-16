pipeline {
  agent any
  stages {
    stage('checkout-code') {
      agent any
      steps {
        git(url: 'https://github.com/Abdallah-Zidan/curriculum-app', branch: 'dev')
      }
    }

  }
}