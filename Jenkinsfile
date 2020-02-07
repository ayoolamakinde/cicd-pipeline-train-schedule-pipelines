pipeline {
  agent any
  stages {
    stages ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-daemon'
        archiveArtificats artifacts: 'dist/trainSchedule.zip'
       }
     }
   }
 }
