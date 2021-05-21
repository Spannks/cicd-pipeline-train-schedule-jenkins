pipleline {
  agent any
  stages {
    stage ('Build') {
      steps {
      echo 'Running build'
        sh './gradlew build --no-deamon'
        achiveArtifacts artifacts: 'dist/trainSchedule.zip'   
      }
    }
 }
}
