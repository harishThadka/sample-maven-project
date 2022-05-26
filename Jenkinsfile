pipeline{
  agent any
    stages {
    stage('Install') {
      steps {
        withMaven(jdk: 'Java11', maven: 'JenkinsMaven', mavenSettingsConfig: 'MavenSettings') {
          sh 'mvn clean install'
      }
      }
    }
  }
}
