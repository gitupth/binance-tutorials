pipeline {
  agent {
    dockerfile {
      filename 'data'
    }

  }
  stages {
    stage('') {
      steps {
        node(label: 'data') {
          ws(dir: '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') {
            sh 'ls -l'
          }

        }

      }
    }

  }
}