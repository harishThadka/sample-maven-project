pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'Java11', maven: 'Maven3', mavenSettingsConfig: 'null', mavenSettingsFilePath: ' ${user.home}/.m2/settings.xml') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
