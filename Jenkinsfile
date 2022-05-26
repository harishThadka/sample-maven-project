pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(jdk: 'Java11', maven: 'Maven3') {
          bat 'mvn clean install'
      }
      }
    }
  }
}
