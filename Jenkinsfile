pipeline {
  agent any
  stages {
    stage('Say Hello') {
      parallel {
        stage('Say Hello') {
          steps {
            echo 'See, Adam? It works.'
          }
        }

        stage('Say Goodbye') {
          steps {
            echo 'I don\'t why you say hello.'
          }
        }

      }
    }

  }
}