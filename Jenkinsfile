pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'settings.xml', jdk: 'Java11', maven: 'JenkinsMaven', mavenSettingsConfig: 'MavenSettings') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
