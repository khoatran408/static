pipeline {
     agent any
     stages {
         stage('Security Scan') {
              steps { 
                 aquaMicroscanner imageName: 'nginx', notCompliesCmd: 'exit 1', onDisallowed: 'fail', outputFormat: 'html'
              }
         }
     }
}
