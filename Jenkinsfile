pipeline {
  agent any
  stages {
    stage('build') {
      agent any
      steps {
        sh 'echo "hello"'
      }
    }

    stage('test') {
      agent any
      steps {
        echo '"this is from test stage"'
        sleep 2
      }
    }

    stage('deploy') {
      agent any
      steps {
        sh 'echo "this is from deploy"'
      }
    }

  }
}