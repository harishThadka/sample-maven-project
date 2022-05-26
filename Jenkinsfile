pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(jdk: 'Java11', maven: 'Maven3') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
