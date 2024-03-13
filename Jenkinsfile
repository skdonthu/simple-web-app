pipeline {
  agent any
  stages {
    stage('source') {
      parallel {
        stage('source') {
          steps {
            echo 'Hello'
          }
        }

        stage('loading') {
          steps {
            echo 'This is satish'
          }
        }

      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'code building'
          }
        }

        stage('Code build') {
          steps {
            echo 'executing'
          }
        }

      }
    }

    stage('Resource') {
      steps {
        echo 'code checking'
      }
    }

    stage('webhook') {
      steps {
        echo 'to add the webhook to code'
      }
    }

    stage('testing') {
      steps {
        echo 'testing the whole code'
      }
    }

  }
}