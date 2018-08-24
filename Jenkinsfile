pipeline{
  agent any
  stages {
    stage ('Build'){
      steps {
        echo 'its building the file woot'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
    }
  }
}
