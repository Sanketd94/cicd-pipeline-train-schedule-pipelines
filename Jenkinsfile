pipeline {
  agent any
stages {
stage {'build'} {
  steps {
    echo 'Running build automatically'
   sh './gradelw build --no-daemon'
    archiveArtifacts artifacts: 'dist/trainSchedule.zip'
  }
}
}
}
