pipeline {
  agent any
  stages {
    stage('Development Build') {
      steps {
        build 'helloworld'
        echo 'Build COmpleted'
        sh 'echo "Hellow ORlds"'
      }
    }
  }
}