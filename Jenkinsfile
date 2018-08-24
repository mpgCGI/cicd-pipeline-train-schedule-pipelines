pipeline{
  agent any
  stages {
    stage ('build'){
      steps {
        echo 'it's building the file, woot!'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
       }
    }
  }
}
