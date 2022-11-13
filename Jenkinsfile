pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'hiii'
          }
        }

        stage('stage2') {
          steps {
            echo 'varsha'
          }
        }

      }
    }

    stage('stage2') {
      parallel {
        stage('stage2') {
          steps {
            echo 'ajinkya'
          }
        }

        stage('pingle') {
          steps {
            echo 'me'
          }
        }

      }
    }

  }
}