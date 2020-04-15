pipeline {
      agent any
      stages {
          stage('Upload to AWS.') {
              steps {
                  sh 'echo "Hello World"'
                  sh '''
                     echo "Multiline shell seeps works too"
                     ls -lah
                  '''
              }
          }
      }
}
