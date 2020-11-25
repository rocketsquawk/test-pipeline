pipeline {
  agent any
  stages {
    stage('I don\'t know why') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'See, Adam? It works.'
          }
        }

        stage('Say Goodbye') {
          steps {
            echo 'I don\'t know why you say hello.'
          }
        }

      }
    }

  }
}