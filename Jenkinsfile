pipeline{
  agent any
  stages{
    stage('scm-checkout') {
      steps{
        git 'https://github.com/tirupathi-naidu/maven-project'
      }
    }
    stage('build') {
      steps{
        sh 'mvn clean install'
      }
    }
  }
}
     
