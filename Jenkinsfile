
 pipeline{
   agent{
        node { label 'workstation'}
        }
    stages {
      stage ('unit tests') {
        steps {
         sh 'mvn package'
        }
      }
      stage ('Code Analysis') {
         steps {
            echo 'Code Analysis'
         }
      }

      stage ('Security Scans') {
         steps {
            echo 'Security Scans'
          }
      }

      stage ('Publish a Artifact') {
        steps {
            echo 'Publish a Artifact'
        }
     }
    }

  }
