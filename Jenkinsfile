pipeline {
  agent {
    docker { image 'maven:3.8.1-adoptopenjdk-11' } 

  stages {
    stage("Build") {
      steps {
	sh "mvn -version"
	sh "mvn clean install"
      }
    }
  }
}
