pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'Java11', maven: 'Maven3', mavenSettingsConfig: 'null') {
            // some block
        }
      }
    }
  }
}
