pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'Java11', maven: 'Maven3', mavenSettingsConfig: 'null', mavenSettingsFilePath: '$MAVEN_HOME/conf/settings.xml') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
