pipleline {
  agent any
  stages {
    stage ('Build') {
      Steps {
      echo 'Running build'
        sh './gradlew build --no-deamon'
        achiveArtifacts artifacts: 'dist/trainSchedule.zip'   
      }
    }
 }
}
