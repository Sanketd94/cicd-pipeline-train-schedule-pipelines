pipeline {
  agent any
stages {
stage {'Build'} {
  steps {
    echo 'Running build automatically'
   sh './gradelw build --no-daemon'
    archiveArtifacts Artifacts: 'dist/trainSchedule.zip'
  }
}
}
}
