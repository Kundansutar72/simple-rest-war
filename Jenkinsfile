pipeline {
  agent any
  environment {
    PATH = "/opt/maven/bin:$PATH"
  }
  stages {
    stage('Build War') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}
