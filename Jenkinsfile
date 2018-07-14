pipline {
  agent any
  stages {
   stage ('Build') {
     steps {
       echo 'Running build automatiion'
       sh './gradlew build --no daemon'
       archiveArtifacts artifcats: 'dist/trainSchedule.zip'
  
  }
}
}

}
