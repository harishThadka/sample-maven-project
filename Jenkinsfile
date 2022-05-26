pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'Maven3', mavenSettingsConfig: 'null') {
          sh 'mvn clean install'
        }
      }
    }
  }
}
