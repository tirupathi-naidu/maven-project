pipeline{
  agent any
  tools{
    maven "MAVEN"
  }
  stages{
    stage('scm-checkout') {
      steps{
        git 'https://github.com/tirupathi-naidu/maven-project'
      }
    }
    stage('build') {
      steps{
        sh 'mvn package'
      }
    }
  }
}
     
