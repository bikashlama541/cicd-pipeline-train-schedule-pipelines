pipeline{
  agent any
  stages{
    stage('Build')
    {
       steps {
          echo " Running the build stage "
          echo " -----------------------"
          sh ' ./gradlew build --no-daemon '
          Archieveartifact arhieve:dist/trainSchedule.zip
    }
  }
  
}
