pipeline {
  agent {
    dockerfile {
      filename 'data'
    }

  }
  stages {
    stage('transfere') {
      steps {
        node(label: 'data')
      }
    }

  }
}