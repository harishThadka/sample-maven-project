pipeline{
  agent any
    stages {
    stage('Compile') {
      steps {
        withMaven(jdk: 'Java11', maven: 'Maven3') {
          bat 'mvn clean compile'
      }
      }
    }
    stage('Test') {
      steps {
        withMaven(jdk: 'Java11', maven: 'Maven3') {
          bat 'mvn test'
      }
      }
    }
    stage('Deploy') {
      steps {
        withMaven(jdk: 'Java11', maven: 'Maven3') {
          bat 'mvn deploy'
      }
      }
    }
  }
}
