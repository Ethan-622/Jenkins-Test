pipeline {
  agent {
    node {
      label 'agent'
    }

  }
  stages {
    stage('stage') {
      steps {
        sh 'echo "This is stage"'
      }
    }

    stage('test') {
      steps {
        sh 'echo "test step"'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "deploy step"'
      }
    }

    stage('finish') {
      steps {
        sh 'echo "Finish"'
      }
    }

  }
}