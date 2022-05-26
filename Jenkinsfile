pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(globalMavenSettingsConfig: 'null', jdk: 'Java11', maven: 'JenkinsMaven', mavenSettingsConfig: 'null') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
