pipeline {
  agent any
  stages {
     stage ('Build') {
        steps { 
           echo 'Build the pipeline'
           sh   './gradlew build --no-daemon'
        }
     }
  }
}

