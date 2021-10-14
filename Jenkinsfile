pipeline {
    agent any 
    stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'Maven3')  {
    sh 'make' 
    archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
}
    }
  }

}


