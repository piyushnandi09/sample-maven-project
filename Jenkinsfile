pipeline {
    agent any 
    stages {
  stage('maven install') {
    steps {
      withMaven(maven: 'Maven 3')  {
    sh 'mvn clean install'
}
}
    }
  }

}


