pipeline {
     agent any
     stages {
         stage('Security Scan') {
              steps { 
                 aquaMicroscanner imageName: 'nginx:latest', notCompliesCmd: 'exit 1', onDisallowed: 'fail', outputFormat: 'html'
              }
         }
     }
}
