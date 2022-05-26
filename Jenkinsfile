pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'Java11', maven: 'JenkinsMaven', mavenSettingsConfig: 'MavenSettings') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
