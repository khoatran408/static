pipeline {
     agent any
     stages {
         stage('Security Scan') {
              steps { 
                 aquaMicroscanner imageName: 'nginx:stable', notCompliesCmd: 'exit 1', onDisallowed: 'fail', outputFormat: 'html'
              }
         }
     }
}
