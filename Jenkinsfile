pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      steps {
        echo 'Buzz Buzz'
      }
    }

    stage('Bees Bees') {
      parallel {
        stage('Bees Bees') {
          steps {
            echo 'Bees Bees'
          }
        }

        stage('test1') {
          steps {
            echo 'hello test1'
          }
        }

        stage('test2') {
          steps {
            echo 'echo "hello"'
          }
        }

        stage('test3') {
          steps {
            sleep 10
          }
        }

      }
    }

  }
}